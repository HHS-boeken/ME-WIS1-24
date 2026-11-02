# 6. Exponentiële functies

:::{code-cell} ipython3
:tags: ["hide-input"]

import numpy as np
import matplotlib.pyplot as plt
import ipywidgets as widgets
from IPython.display import display, clear_output
from matplotlib_inline.backend_inline import set_matplotlib_formats

# Scherpe vectorafbeelding
set_matplotlib_formats('svg')


# Sliders
a_slider = widgets.FloatSlider(
    value=1,
    min=-3,
    max=3,
    step=0.5,
    description=r'a:',
    continuous_update=True
)

b_slider = widgets.FloatSlider(
    value=2,
    min=0.5,
    max=3,
    step=0.5,
    description=r'b:',
    continuous_update=True
)

p_slider = widgets.FloatSlider(
    value=0,
    min=-5,
    max=5,
    step=0.5,
    description=r'p:',
    continuous_update=True
)

q_slider = widgets.FloatSlider(
    value=0,
    min=-5,
    max=5,
    step=0.5,
    description=r'q:',
    continuous_update=True
)

output = widgets.Output()


# Mooie formule maken
def formule(a, b, p, q):
    # a
    if a == 1:
        a_deel = ""
    elif a == -1:
        a_deel = "-"
    else:
        a_deel = rf"{a:g}\cdot "

    # exponent x - p
    if p > 0:
        exponent = f"x-{p:g}"
    elif p < 0:
        exponent = f"x+{abs(p):g}"
    else:
        exponent = "x"

    # q
    if q > 0:
        q_deel = f"+{q:g}"
    elif q < 0:
        q_deel = f"-{abs(q):g}"
    else:
        q_deel = ""

    return rf"$f(x)={a_deel}{b:g}^{{{exponent}}}{q_deel}$"


def teken(change=None):
    with output:
        clear_output(wait=True)

        a = a_slider.value
        b = b_slider.value
        p = p_slider.value
        q = q_slider.value

        x = np.linspace(-10, 10, 1000)
        y = a * b**(x - p) + q

        fig, ax = plt.subplots(figsize=(7, 7))

        # Grafiek
        ax.plot(
            x,
            y,
            linewidth=2.2
        )

        # Venster
        ax.set_xlim(-10, 10)
        ax.set_ylim(-10, 10)

        # Zelfde schaal op beide assen
        ax.set_aspect('equal', adjustable='box')

        # Raster
        ax.set_xticks(np.arange(-10, 11, 1))
        ax.set_yticks(np.arange(-10, 11, 1))
        ax.grid(
            True,
            linewidth=0.5,
            alpha=0.25
        )

        # Assen door de oorsprong
        ax.spines['left'].set_position('zero')
        ax.spines['bottom'].set_position('zero')

        ax.spines['right'].set_visible(False)
        ax.spines['top'].set_visible(False)

        ax.spines['left'].set_linewidth(1.2)
        ax.spines['bottom'].set_linewidth(1.2)

        # Getallen bij de assen
        ax.tick_params(
            axis='both',
            which='major',
            labelsize=9
        )

        # Formule boven de grafiek
        ax.set_title(
            formule(a, b, p, q),
            fontsize=16,
            pad=18
        )

        plt.show()
        plt.close(fig)


# Sliders koppelen aan grafiek
for slider in [a_slider, b_slider, p_slider, q_slider]:
    slider.observe(teken, names='value')


# Tonen
display(
    widgets.VBox([
        a_slider,
        b_slider,
        p_slider,
        q_slider,
        output
    ])
)

teken()
:::