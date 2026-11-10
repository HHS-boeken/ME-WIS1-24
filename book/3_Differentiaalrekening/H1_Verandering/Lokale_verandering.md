# 1.3 Lokale verandering

:::{admonition} Theorie
:class: tip, dropdown open

**Lokale verandering en differentiaalquotiënt**

In de vorige paragraaf hebben we de gemiddelde verandering van een functie berekend met het differentiequotiënt. Op het variabele interval $[a,a+h]$ gebruikten we:

$$
\dfrac{\Delta y}{\Delta x}=\dfrac{f(a+h)-f(a)}{h}
$$

Hierbij geldt $h\neq 0$.

Wanneer we $h$ steeds kleiner maken, liggen de twee punten op de grafiek steeds dichter bij elkaar. De gemiddelde verandering nadert dan, als deze bestaat, de **lokale verandering** in het punt waar $x=a$.

De lokale verandering noemen we het **differentiaalquotiënt**. We gebruiken hiervoor de notatie $\dfrac{\dd f}{\dd x}(a)$. Dit betekent dat we $\dfrac{\dd f}{\dd x}$ bepalen bij $x=a$.

Eerst werken we het differentiequotiënt zo ver mogelijk uit, zodat $h$ niet meer in de noemer staat. Vervolgens onderzoeken we wat er gebeurt wanneer $h\to 0$:

$$
\dfrac{\Delta y}{\Delta x}\xrightarrow{h\to 0}\dfrac{\dd f}{\dd x}(a)
$$

Let op: we delen nooit door $h=0$. We vereenvoudigen de breuk **voordat** we $h$ naar nul laten gaan.

Grafisch is de lokale verandering gelijk aan de **richtingscoëfficiënt van de raaklijn** aan de grafiek bij $x=a$.

:::

## 1.3.1 Lokale verandering in een punt

:::{admonition} Voorbeeld 1
:class: dropdown

Gegeven is de functie:

$$
f(x)=x^2+2x
$$

Bereken de lokale verandering bij $x=1$ met behulp van het differentiequotiënt op het interval $[1,1+h]$.

**Uitwerking**

De formule voor het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\dfrac{f(1+h)-f(1)}{h}
$$

We berekenen eerst de functiewaarden:

$$
\begin{align*}
f(1)&=1^2+2\cdot1\\
&=3
\end{align*}
$$

$$
\begin{align*}
f(1+h)&=(1+h)^2+2(1+h)\\
&=1+2h+h^2+2+2h\\
&=3+4h+h^2
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(1+h)-f(1)}{h}\\
&=\dfrac{3+4h+h^2-3}{h}\\
&=\dfrac{4h+h^2}{h}\\
&=4+h
\end{align*}
$$

Wanneer $h$ naar nul gaat, nadert $4+h$ de waarde $4$:

$$
h\to 0\quad\Rightarrow\quad 4+h\to 4
$$

Dus:

$$
\boxed{\dfrac{\dd f}{\dd x}(1)=4}
$$

De lokale verandering bij $x=1$ is dus **4**. De raaklijn aan de grafiek heeft daar richtingscoëfficiënt **4**.
:::
:::

:::{admonition} Oefening 1
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=4x-3
$$

Bereken de lokale verandering bij $x=2$ met behulp van het differentiequotiënt op het interval $[2,2+h]$.

:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\dfrac{f(2+h)-f(2)}{h}
$$

We berekenen eerst de functiewaarden:

$$
\begin{align*}
f(2)&=4\cdot2-3\\
&=5
\end{align*}
$$

$$
\begin{align*}
f(2+h)&=4(2+h)-3\\
&=5+4h
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(2+h)-f(2)}{h}\\
&=\dfrac{5+4h-5}{h}\\
&=\dfrac{4h}{h}\\
&=4
\end{align*}
$$

Als $h\to0$, blijft de uitkomst $4$. Dus:

$$
\boxed{\dfrac{\dd f}{\dd x}(2)=4}
$$
:::
:::

:::{admonition} Oefening 2
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=x^2-2x+3
$$

Bereken de lokale verandering bij $x=3$ met behulp van het differentiequotiënt op het interval $[3,3+h]$.

:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\dfrac{f(3+h)-f(3)}{h}
$$

We berekenen eerst de functiewaarden:

$$
\begin{align*}
f(3)&=3^2-2\cdot3+3\\
&=6
\end{align*}
$$

$$
\begin{align*}
f(3+h)&=(3+h)^2-2(3+h)+3\\
&=9+6h+h^2-6-2h+3\\
&=6+4h+h^2
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(3+h)-f(3)}{h}\\
&=\dfrac{6+4h+h^2-6}{h}\\
&=\dfrac{4h+h^2}{h}\\
&=4+h
\end{align*}
$$

Als $h\to0$, dan nadert $4+h$ de waarde $4$. Dus:

$$
\boxed{\dfrac{\dd f}{\dd x}(3)=4}
$$
:::
:::

:::{admonition} Oefening 3
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=-2x^2+3x+1
$$

Bereken de lokale verandering bij $x=-1$ met behulp van het differentiequotiënt op het interval $[-1,-1+h]$.

:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\dfrac{f(-1+h)-f(-1)}{h}
$$

Bereken eerst de functiewaarden:

$$
\begin{align*}
f(-1)&=-2(-1)^2+3(-1)+1\\
&=-2-3+1\\
&=-4
\end{align*}
$$

$$
\begin{align*}
f(-1+h)&=-2(-1+h)^2+3(-1+h)+1\\
&=-2(1-2h+h^2)-3+3h+1\\
&=-2+4h-2h^2-3+3h+1\\
&=-4+7h-2h^2
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{f(-1+h)-f(-1)}{h}\\
&=\dfrac{-4+7h-2h^2-(-4)}{h}\\
&=\dfrac{7h-2h^2}{h}\\
&=7-2h
\end{align*}
$$

Als $h\to0$, dan nadert $7-2h$ de waarde $7$. Dus:

$$
\boxed{\dfrac{\dd f}{\dd x}(-1)=7}
$$
:::
:::


## 1.3.2 Van lokale verandering naar de afgeleide functie

:::{admonition} Voorbeeld 2
:class: dropdown

Gegeven is de functie:

$$
f(x)=x^2+2x
$$

Bepaal de afgeleide functie met behulp van het differentiequotiënt op het interval $[x,x+h]$.

:::{admonition} Uitwerking
:class: dropdown

De formule voor het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\dfrac{f(x+h)-f(x)}{h}
$$

Bereken de functiewaarden:

$$
\begin{aligned}
f(x+h)&=(x+h)^2+2(x+h)\\
&=x^2+2xh+h^2+2x+2h
\end{aligned}
$$

Invullen geeft:

$$
\begin{aligned}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{x^2+2xh+h^2+2x+2h-(x^2+2x)}{h}\\[4pt]
&=\dfrac{2xh+h^2+2h}{h}\\[4pt]
&=2x+h+2
\end{aligned}
$$

Wanneer $h\to0$, nadert $2x+h+2$ de waarde $2x+2$.

De **afgeleide functie** is dus:

$$
\boxed{\dfrac{\dd f}{\dd x}=2x+2}
$$

Met deze formule kunnen we de lokale verandering bij elke waarde van $x$ berekenen. Bijvoorbeeld bij $x=1$:

$$
\dfrac{\dd f}{\dd x}(1)=2\cdot1+2=4
$$

Dit is dezelfde uitkomst als in voorbeeld 1.
:::
:::

:::{admonition} Oefening 4
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=-3x+5
$$

Bepaal de afgeleide functie met behulp van het differentiequotiënt op het interval $[x,x+h]$.

:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\dfrac{f(x+h)-f(x)}{h}
$$

Bereken eerst de functiewaarden:

$$
\begin{aligned}
f(x+h)&=-3(x+h)+5\\
&=-3x-3h+5
\end{aligned}
$$

Invullen geeft: 

$$
\begin{aligned}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{-3x-3h+5-(-3x+5)}{h}\\[4pt]
&=\dfrac{-3h}{h}\\[4pt]
&=-3
\end{aligned}
$$

Als $h\to0$, blijft de uitkomst $-3$. Dus:

$$
\boxed{\dfrac{\dd f}{\dd x}=-3}
$$
:::
:::

:::{admonition} Oefening 5
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=x^2-4x+2
$$

Bepaal de afgeleide functie met behulp van het differentiequotiënt op het interval $[x,x+h]$.

:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\dfrac{f(x+h)-f(x)}{h}
$$

Bereken eerst de functiewaarden:

$$
\begin{aligned}
f(x+h)&=(x+h)^2-4(x+h)+2\\
&=x^2+2xh+h^2-4x-4h+2
\end{aligned}
$$

Invullen geeft:

$$
\begin{aligned}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{x^2+2xh+h^2-4x-4h+2-(x^2-4x+2)}{h}\\[4pt]
&=\dfrac{2xh+h^2-4h}{h}\\[4pt]
&=2x+h-4
\end{aligned}
$$

Als $h\to0$, nadert $2x+h-4$ de waarde $2x-4$. Dus:

$$
\boxed{\dfrac{\dd f}{\dd x}=2x-4}
$$
:::
:::

:::{admonition} Oefening 6
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=-2x^2+3x+1
$$

Bepaal de afgeleide functie met behulp van het differentiequotiënt op het interval $[x,x+h]$. Controleer daarna je antwoord door de lokale verandering bij $x=-1$ te berekenen.

:::{dropdown} Uitwerking

De formule voor het differentiequotiënt is:

$$
\dfrac{\Delta y}{\Delta x}=\dfrac{f(x+h)-f(x)}{h}
$$

Bereken eerst de functiewaarden:

$$
\begin{aligned}
f(x+h)&=-2(x+h)^2+3(x+h)+1\\
&=-2(x^2+2xh+h^2)+3x+3h+1\\
&=-2x^2-4xh-2h^2+3x+3h+1
\end{aligned}
$$

Invullen geeft: 

$$
\begin{aligned}
\dfrac{\Delta y}{\Delta x}
&=\dfrac{-2x^2-4xh-2h^2+3x+3h+1-(-2x^2+3x+1)}{h}\\[4pt]
&=\dfrac{-4xh-2h^2+3h}{h}\\[4pt]
&=-4x-2h+3
\end{aligned}
$$

Als $h\to0$, nadert $-4x-2h+3$ de waarde $-4x+3$. Dus:

$$
\boxed{\dfrac{\dd f}{\dd x}=-4x+3}
$$

Controle bij $x=-1$:

$$
\dfrac{\dd f}{\dd x}(-1)=-4(-1)+3=7
$$

Dit is dezelfde uitkomst als in oefening 3.
:::
:::
