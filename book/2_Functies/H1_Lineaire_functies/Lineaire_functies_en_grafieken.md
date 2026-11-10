# 1.1 Lineaire functies en grafieken


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
def formule(a, p, q):
    # a
    if a == 1:
        a_deel = ""
    elif a == -1:
        a_deel = "-"
    else:
        a_deel = f"{a:g}"

    # p
    if p > 0:
        p_deel = f"(x-{p:g})"
    elif p < 0:
        p_deel = f"(x+{abs(p):g})"
    else:
        p_deel = "x"

    # q
    if q > 0:
        q_deel = f"+{q:g}"
    elif q < 0:
        q_deel = f"-{abs(q):g}"
    else:
        q_deel = ""

    return rf"$f(x)={a_deel}{p_deel}^2{q_deel}$"


def teken(change=None):
    with output:
        clear_output(wait=True)

        a = a_slider.value
        p = p_slider.value
        q = q_slider.value

        x = np.linspace(-10, 10, 1000)
        y = a * (x - p)**2 + q

        fig, ax = plt.subplots(figsize=(7, 7))

        # Grafiek
        ax.plot(
            x,
            y,
            linewidth=2.2
        )

        # Top
        ax.scatter(
            p,
            q,
            s=45,
            zorder=5
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
            formule(a, p, q),
            fontsize=16,
            pad=18
        )

        plt.show()
        plt.close(fig)


# Sliders koppelen aan grafiek
for slider in [a_slider, p_slider, q_slider]:
    slider.observe(teken, names='value')


# Tonen
display(
    widgets.VBox([
        a_slider,
        p_slider,
        q_slider,
        output
    ])
)

teken()
:::

