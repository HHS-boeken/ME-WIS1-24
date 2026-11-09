# 1.2 Gemiddelde verandering

:::{admonition} Theorie
:class: tip, dropdown open

**Gemiddelde verandering en differentiequotiënt**

Met de totale verandering van een functie berekenen we hoeveel de functiewaarde verandert tussen twee punten. Soms willen we echter niet alleen weten hoeveel de functiewaarde verandert, maar ook hoe groot deze verandering gemiddeld is per eenheid $x$.

Dit noemen we de **gemiddelde verandering**.

De gemiddelde verandering berekenen we door de totale verandering van de functiewaarde te delen door de verandering van $x$.

$$
\text{Gemiddelde verandering}=\dfrac{\Delta y}{\Delta x}
$$

Bij een functie $f(x)$ op het interval $[a,b]$ geldt:

$$
\Delta x=b-a
$$

en

$$
\Delta y=f(b)-f(a)
$$

Hiermee krijgen we:

$$
\boxed{\dfrac{\Delta y}{\Delta x}=\dfrac{f(b)-f(a)}{b-a}}
$$

Deze verhouding noemen we het **differentiequotiënt**.

Het differentiequotiënt geeft de gemiddelde verandering van een functie op een interval. Grafisch is dit gelijk aan de richtingscoëfficiënt van de rechte lijn door de twee punten van de grafiek die bij de uiteinden van het interval horen.

**Het differentiequotiënt met een variabel interval**

Tot nu toe berekenden we het differentiequotiënt op een interval met twee vaste grenswaarden. We kunnen het interval echter ook variabel maken.

Hiervoor gebruiken we het interval $[a,a+h]$, waarbij $h>0$ de lengte van het interval voorstelt.

Omdat:

$$
\Delta x=(a+h)-a=h
$$

kunnen we het differentiequotiënt schrijven als:

$$
\boxed{\dfrac{\Delta y}{\Delta x}=\dfrac{f(a+h)-f(a)}{h}}
$$

Hierbij geldt $h\neq 0$.

Door de waarde van $h$ te veranderen, kunnen we onderzoeken hoe de gemiddelde verandering afhankelijk is van de lengte van het interval.
:::

## 1.2.1 Vast interval $[2, 4]$

::::{admonition} Voorbeeld 1
:class: dropdown

Gegeven is de functie:

$$
f(x)=x^2
$$

Bereken het differentiequotiënt op het interval $[2,4]$. 

**Uitwerking**

De formule voor het differentiequotiënt is: 

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(b)-f(a)}{b-a}\\
\end{align*}
$$

We berekenen eerst de functiewaarden:

$$
\begin{align*}
f(2)&=2^2\\
&=4
\end{align*}
$$

$$
\begin{align*}
f(4)&=4^2\\
&=16
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(4)-f(2)}{4-2}\\
&=\dfrac{16 - 4}{2}\\
&=6
\end{align*}
$$

Dus het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x} =\boxed{6}
$$

De gemiddelde verandering (differentiequotiënt) op het interval $[2,4]$ is dus 6 per eenheid $x$.
::::


::::{admonition} Oefening 1
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=3x-2
$$

Bereken het differentiequotiënt op het interval $[1,5]$.

:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(b)-f(a)}{b-a}
\end{align*}
$$

We berekenen eerst de functiewaarden:

$$
\begin{align*}
f(1)&=3\cdot1-2\\
&=1
\end{align*}
$$

$$
\begin{align*}
f(5)&=3\cdot5-2\\
&=13
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(5)-f(1)}{5-1}\\
&=\dfrac{13-1}{4}\\
&=\dfrac{12}{4}\\
&=3
\end{align*}
$$

Dus het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\boxed{3}
$$

:::
::::

::::{admonition} Oefening 2
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=x^2+2x-1
$$

Bereken het differentiequotiënt op het interval $[1,4]$.

:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(b)-f(a)}{b-a}
\end{align*}
$$

We berekenen eerst de functiewaarden:

$$
\begin{align*}
f(1)&=1^2+2\cdot1-1\\
&=2
\end{align*}
$$

$$
\begin{align*}
f(4)&=4^2+2\cdot4-1\\
&=16+8-1\\
&=23
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(4)-f(1)}{4-1}\\
&=\dfrac{23-2}{3}\\
&=\dfrac{21}{3}\\
&=7
\end{align*}
$$

Dus het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\boxed{7}
$$

:::
::::

::::{admonition} Oefening 3
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=-2x^2+3x+4
$$

Bereken het differentiequotiënt op het interval $[-1,3]$.

:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(b)-f(a)}{b-a}
\end{align*}
$$

We berekenen eerst de functiewaarden:

$$
\begin{align*}
f(-1)&=-2\cdot(-1)^2+3\cdot(-1)+4\\
&=-2-3+4\\
&=-1
\end{align*}
$$

$$
\begin{align*}
f(3)&=-2\cdot3^2+3\cdot3+4\\
&=-18+9+4\\
&=-5
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(3)-f(-1)}{3-(-1)}\\
&=\dfrac{-5-(-1)}{4}\\
&=\dfrac{-4}{4}\\
&=-1
\end{align*}
$$

Dus het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\boxed{-1}
$$

:::
::::


## 1.2.2 Variabel interval $[2, 2+h]$


::::{admonition} Voorbeeld 2
:class: dropdown

Gegeven is de functie:

$$
f(x)=x^2
$$

Bereken het differentiequotiënt op het interval $[2,2+h]$. Schrijf je antwoord zo eenvoudig mogelijk.

**Uitwerking**

De formule voor het differentiequotiënt is: 

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(2+h)-f(2)}{h}\\
\end{align*}
$$

We berekenen eerst de functiewaarden:

$$
\begin{align*}
f(2)&=2^2\\
&=4
\end{align*}
$$

$$
\begin{align*}
f(2+h)&=(2+h)^2\\
&=4+4h+h^2
\end{align*}
$$

Invullen geeft:


$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(2+h)-f(2)}{h}\\
&=\dfrac{4+4h+h^2-4}{h}\\
&=\dfrac{4h+h^2}{h}\\
&=4+h
\end{align*}
$$

Dus het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x} =\boxed{4+h}
$$

Het differentiequotiënt is nu afhankelijk van $h$.

Voor $h=2$ krijgen we:

$$
\dfrac{\Delta y}{\Delta x}=4+2=6
$$

Dit is hetzelfde resultaat als in voorbeeld 1, omdat het interval $[2,2+h]$ voor $h=2$ gelijk is aan $[2,4]$.

Wanneer we $h$ kleiner maken, berekenen we de gemiddelde verandering over een steeds kleiner interval.

::::

::::{admonition} Oefening 1
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=3x+2
$$

Bereken het differentiequotiënt op het interval $[2,2+h]$. Schrijf je antwoord zo eenvoudig mogelijk.

:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is: 

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(2+h)-f(2)}{h}\\[6pt]
\end{align*}
$$

Bereken de functiewaarden:

$$
\begin{align*}
f(2)&=3\cdot2+2\\
&=8\\
\end{align*}
$$

$$
\begin{align*}
f(2+h)&=3(2+h)+2\\
&=8+3h
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(2+h)-f(2)}{h}\\
&=\dfrac{8+3h-8}{h}\\
&=\dfrac{3h}{h}\\
&=3
\end{align*}
$$

Dus het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\boxed{3}
$$
:::
::::

::::{admonition} Oefening 2
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=x^2+2x
$$

Bereken het differentiequotiënt op het interval $[2,2+h]$. Schrijf je antwoord zo eenvoudig mogelijk.


:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is: 

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(2+h)-f(2)}{h}\\[6pt]
\end{align*}
$$

Bereken de functiewaarden:

$$
\begin{align*}
f(2)&=2^2+2\cdot2\\
&=8
\end{align*}
$$

$$
\begin{align*}
f(2+h)&=(2+h)^2+2(2+h)\\
&=4+4h+h^2+4+2h\\
&=8+6h+h^2
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(2+h)-f(2)}{h}\\
&=\dfrac{8+6h+h^2-(8)}{h}\\
&=\dfrac{6h+h^2}{h}\\
&=6+h
\end{align*}
$$

Dus het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x} = \boxed{6+h}
$$

:::
::::

::::{admonition} Oefening 3
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=-2x^2+5x-3
$$

Bereken het differentiequotiënt op het interval $[2,2+h]$. Schrijf je antwoord zo eenvoudig mogelijk.


:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is: 

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(2+h)-f(2)}{h}\\[6pt]
\end{align*}
$$

Bereken de functiewaarden:

$$
\begin{align*}
f(2)&=-2\cdot2^2+5\cdot2-3\\
&=-1
\end{align*}
$$

$$
\begin{align*}
f(2+h)&=-2(2+h)^2+5(2+h)-3\\
&=-2(4+4h+h^2)+10+5h-3\\
&=-8-8h-2h^2+10+5h-3\\
&=-1-3h-2h^2
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(2+h) - f(2)}{h}\\
&=\dfrac{-1-3h-2h^2-(-1)}{h}\\
&=\dfrac{-3h - 2h^2}{h}\\
&=-3-2h
\end{align*}
$$

Dus het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x} = \boxed{-3-2h}
$$
:::
::::
