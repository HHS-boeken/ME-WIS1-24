# 4. Wortelfuncties

## **1. Standaardvorm van een Wortelfunctie**
Een wortelfunctie is een functie waarin de variabele $x$ zich onder een wortelteken bevindt. De algemene vorm van een wortelfunctie is:

$$
f(x) = a\sqrt{b(x - h)} + k
$$

waarbij:
- $a$ de verticale uitrekking of inkrimping bepaalt. Als $a < 0$, wordt de grafiek gespiegeld ten opzichte van de x-as.
- $b$ de horizontale uitrekking of inkrimping beïnvloedt.
- $h$ de horizontale verschuiving bepaalt (de grafiek wordt $h$ eenheden naar links of rechts verplaatst).
- $k$
 de verticale verschuiving bepaalt (de grafiek wordt $k$ eenheden omhoog of omlaag verplaatst).

De meest eenvoudige vorm van een wortelfunctie is:

$$
f(x) = \sqrt{x}
$$

Deze functie heeft als domein $x \geq 0 $ en als bereik $y \geq 0 $, omdat de vierkantswortel van een negatief getal in het domein van reële getallen niet gedefinieerd is.

## **2. Effect van transformaties**

### **Effect van \( a \): Verticale uitrekking, inkrimping en spiegeling**
- **Als \( a > 1 \)**: De grafiek wordt verticaal uitgerekt (steiler).
- **Als \( 0 < a < 1 \)**: De grafiek wordt verticaal ingekrompen (minder steil).
- **Als \( a < 0 \)**: De grafiek wordt gespiegeld over de x-as.

**Voorbeelden:**
- \( f(x) = \sqrt{x} \) (standaard)
- \( f(x) = 2\sqrt{x} \) (steilere groei)
- \( f(x) = \frac{1}{2} \sqrt{x} \) (minder steile groei)
- \( f(x) = -\sqrt{x} \) (spiegeling over de x-as)

### **Effect van \( h \): Horizontale verschuiving**
- **Als \( h > 0 \)**: De grafiek schuift \( h \) eenheden naar rechts.
- **Als \( h < 0 \)**: De grafiek schuift \( |h| \) eenheden naar links.

**Voorbeelden:**
- \( f(x) = \sqrt{x} \) (standaard)
- \( f(x) = \sqrt{x - 2} \) (2 eenheden naar rechts)
- \( f(x) = \sqrt{x + 3} \) (3 eenheden naar links)

### **Effect van \( k \): Verticale verschuiving**
- **Als \( k > 0 \)**: De grafiek schuift \( k \) eenheden omhoog.
- **Als \( k < 0 \)**: De grafiek schuift \( |k| \) eenheden omlaag.

**Voorbeelden:**
- \( f(x) = \sqrt{x} \) (standaard)
- \( f(x) = \sqrt{x} + 3 \) (3 eenheden omhoog)
- \( f(x) = \sqrt{x} - 2 \) (2 eenheden omlaag)

### **Effect van \( b \): Horizontale rek en compressie**
- **Als \( b > 1 \)**: De grafiek wordt horizontaal ingekrompen.
- **Als \( 0 < b < 1 \)**: De grafiek wordt horizontaal uitgerekt.

**Voorbeelden:**
- \( f(x) = \sqrt{x} \) (standaard)
- \( f(x) = \sqrt{2x} \) (ingekrompen)
- \( f(x) = \sqrt{0.5x} \) (uitgerekt)

## **3. Extra uitleg met voorbeelden**

Hieronder staan enkele extra voorbeelden om de transformaties beter te begrijpen:

1. **Combinatie van transformaties**: \( f(x) = -2\sqrt{3(x - 1)} + 4 \)
   - De grafiek wordt gespiegeld over de x-as door \( a = -2 \).
   - De grafiek wordt verticaal uitgerekt met een factor 2.
   - De grafiek wordt horizontaal ingekrompen door \( b = 3 \).
   - De grafiek schuift 1 eenheid naar rechts.
   - De grafiek schuift 4 eenheden omhoog.

2. **Een andere combinatie**: \( f(x) = \frac{1}{2} \sqrt{0.5(x + 2)} - 3 \)
   - De grafiek wordt verticaal ingekrompen door \( a = \frac{1}{2} \).
   - De grafiek wordt horizontaal uitgerekt door \( b = 0.5 \).
   - De grafiek schuift 2 eenheden naar links.
   - De grafiek schuift 3 eenheden omlaag.

## **4. Samenvatting**
- **\( a \)**: Bepaalt verticale rek en spiegeling.
- **\( h \)**: Verschuift de grafiek horizontaal.
- **\( k \)**: Verschuift de grafiek verticaal.
- **\( b \)**: Bepaalt horizontale rek of compressie.

Met deze transformaties kun je de grafiek van een wortelfunctie eenvoudig aanpassen aan specifieke situaties!

dd


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
        wortel_deel = rf"\sqrt{{x-{p:g}}}"
    elif p < 0:
        wortel_deel = rf"\sqrt{{x+{abs(p):g}}}"
    else:
        wortel_deel = r"\sqrt{x}"

    # q
    if q > 0:
        q_deel = f"+{q:g}"
    elif q < 0:
        q_deel = f"-{abs(q):g}"
    else:
        q_deel = ""

    return rf"$f(x)={a_deel}{wortel_deel}{q_deel}$"


def teken(change=None):
    with output:
        clear_output(wait=True)

        a = a_slider.value
        p = p_slider.value
        q = q_slider.value

        # Voor een wortelfunctie geldt x >= p
        x = np.linspace(p, 10, 1000)
        y = a * np.sqrt(x - p) + q

        fig, ax = plt.subplots(figsize=(7, 7))

        # Grafiek
        ax.plot(
            x,
            y,
            linewidth=2.2
        )

        # Beginpunt
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