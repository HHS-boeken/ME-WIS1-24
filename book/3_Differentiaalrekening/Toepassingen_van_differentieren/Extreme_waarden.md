# 3.1 Extreme waarden

````{admonition} Theorie
:class: tip, dropdown open

**Lokale extrema bepalen met de afgeleide**

Met de afgeleide kunnen we onderzoeken waar een functie **stijgt** of **daalt**. Daarmee kunnen we ook bepalen of een grafiek een **lokaal minimum** (dal) of een **lokaal maximum** (top) heeft.

- Als $\dfrac{\dd f}{\dd x}>0$, dan is de functie **stijgend**.
- Als $\dfrac{\dd f}{\dd x}<0$, dan is de functie **dalend**.
- Als $\dfrac{\dd f}{\dd x}=0$, dan is de raaklijn **horizontaal**. Op die plaats kan een lokaal minimum of maximum liggen.

We bepalen een mogelijk lokaal minimum of maximum in vier stappen:

1. **Bepaal de afgeleide** $\dfrac{\dd f}{\dd x}$.
2. **Stel de afgeleide gelijk aan nul** en bereken de bijbehorende waarde(n) van $x$.
3. **Maak een tekenschema** van de afgeleide. Onderzoek of de afgeleide links en rechts van de gevonden waarde positief of negatief is.
4. **Bereken de functiewaarde** om de coördinaten van het minimum of maximum te vinden.

Het tekenschema geeft aan wat er gebeurt:

| Teken van de afgeleide | Verloop van de functie | Conclusie |
|:---:|:---:|:---|
| $-\;\to\;0\;\to\;+$ | Dalend $\to$ stijgend | Lokaal **minimum** (dal) |
| $+\;\to\;0\;\to\;-$ | Stijgend $\to$ dalend | Lokaal **maximum** (top) |
| Geen tekenwisseling | Geen omslag van stijgen naar dalen of omgekeerd | Geen lokaal minimum of maximum |

**Let op:** alleen $\dfrac{\dd f}{\dd x}=0$ is niet genoeg om te concluderen dat er een minimum of maximum is. Controleer altijd het teken van de afgeleide aan beide kanten.

````

## 3.1.1 Lokale minima en maxima bepalen

```{admonition} Voorbeeld 1
:class: dropdown

Gegeven is de functie:

$$
f(x)=-x^3+3x^2+9x-2
$$

Bepaal met behulp van de afgeleide en een tekenschema alle lokale minima en maxima. Bereken ook de coördinaten.

**Uitwerking**

We bepalen eerst de afgeleide:

$$
\dfrac{\dd f}{\dd x}=-3x^2+6x+9
$$

Stel de afgeleide gelijk aan nul:

$$
\begin{align*}
-3x^2+6x+9&=0\\
-3(x^2-2x-3)&=0\\
-3(x+1)(x-3)&=0\\
x&=-1\quad\text{of}\quad x=3
\end{align*}
$$

We onderzoeken het teken van de afgeleide op de drie intervallen:

- Bij $x=-2$: $\dfrac{\dd f}{\dd x}=-3(-2+1)(-2-3)=-15<0$ (dalend).
- Bij $x=0$: $\dfrac{\dd f}{\dd x}=-3(0+1)(0-3)=9>0$ (stijgend).
- Bij $x=4$: $\dfrac{\dd f}{\dd x}=-3(4+1)(4-3)=-15<0$ (dalend).

Dit geeft het volgende **tekenschema**:

| $x$ | $x<-1$ | $x=-1$ | $-1<x<3$ | $x=3$ | $x>3$ |
|:---:|:---:|:---:|:---:|:---:|:---:|
| $\dfrac{\dd f}{\dd x}$ | $-$ | $0$ | $+$ | $0$ | $-$ |
| Verloop van $f$ | Dalend | Lokaal minimum | Stijgend | Lokaal maximum | Dalend |

Bij $x=-1$ verandert de afgeleide van **negatief naar positief**: een lokaal minimum.

Bij $x=3$ verandert de afgeleide van **positief naar negatief**: een lokaal maximum.

Bereken de bijbehorende functiewaarden:

$$
\begin{align*}
f(-1)&=-(-1)^3+3(-1)^2+9(-1)-2\\
&=1+3-9-2\\
&=-7
\end{align*}
$$

$$
\begin{align*}
f(3)&=-3^3+3\cdot3^2+9\cdot3-2\\
&=-27+27+27-2\\
&=25
\end{align*}
$$

Dus het lokale minimum ligt in:

$$
\boxed{(-1,-7)}
$$

En het lokale maximum ligt in:

$$
\boxed{(3,25)}
$$

```

````{admonition} Oefening 1
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=x^3+3x^2-9x+2
$$

Bepaal met behulp van de afgeleide en een tekenschema alle lokale minima en maxima. Bereken ook de coördinaten.

```{dropdown} Uitwerking

We bepalen eerst de afgeleide:

$$
\dfrac{\dd f}{\dd x}=3x^2+6x-9
$$

Stel de afgeleide gelijk aan nul:

$$
\begin{align*}
3x^2+6x-9&=0\\
3(x^2+2x-3)&=0\\
3(x+3)(x-1)&=0\\
x&=-3\quad\text{of}\quad x=1
\end{align*}
$$

We onderzoeken het teken van de afgeleide op de drie intervallen:

- Bij $x=-4$: $\dfrac{\dd f}{\dd x}=3(-4+3)(-4-1)=15>0$ (stijgend).
- Bij $x=0$: $\dfrac{\dd f}{\dd x}=3(0+3)(0-1)=-9<0$ (dalend).
- Bij $x=2$: $\dfrac{\dd f}{\dd x}=3(2+3)(2-1)=15>0$ (stijgend).

Het **tekenschema** is:

| $x$ | $x<-3$ | $x=-3$ | $-3<x<1$ | $x=1$ | $x>1$ |
|:---:|:---:|:---:|:---:|:---:|:---:|
| $\dfrac{\dd f}{\dd x}$ | $+$ | $0$ | $-$ | $0$ | $+$ |
| Verloop van $f$ | Stijgend | Lokaal maximum | Dalend | Lokaal minimum | Stijgend |

Bij $x=-3$ verandert de afgeleide van **positief naar negatief**: een lokaal maximum.

Bij $x=1$ verandert de afgeleide van **negatief naar positief**: een lokaal minimum.

Bereken beide functiewaarden:

$$
\begin{align*}
f(-3)&=(-3)^3+3(-3)^2-9(-3)+2\\
&=-27+27+27+2\\
&=29
\end{align*}
$$

$$
\begin{align*}
f(1)&=1^3+3\cdot1^2-9\cdot1+2\\
&=1+3-9+2\\
&=-3
\end{align*}
$$

Dus het lokale maximum ligt in:

$$
\boxed{(-3,29)}
$$

En het lokale minimum ligt in:

$$
\boxed{(1,-3)}
$$

```
````

````{admonition} Oefening 2
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=x^4-4x^3+4x^2-3
$$

Bepaal met behulp van de afgeleide en een tekenschema alle lokale minima en maxima. Bereken ook de coördinaten.

```{dropdown} Uitwerking

We bepalen eerst de afgeleide:

$$
\dfrac{\dd f}{\dd x}=4x^3-12x^2+8x
$$

Stel de afgeleide gelijk aan nul:

$$
\begin{align*}
4x^3-12x^2+8x&=0\\
4x(x^2-3x+2)&=0\\
4x(x-1)(x-2)&=0\\
x&=0\quad\text{of}\quad x=1\quad\text{of}\quad x=2
\end{align*}
$$

We onderzoeken het teken van de afgeleide op de vier intervallen:

- Bij $x=-1$: $\dfrac{\dd f}{\dd x}=4(-1)(-1-1)(-1-2)=-24<0$ (dalend).
- Bij $x=\dfrac12$: $\dfrac{\dd f}{\dd x}=4\cdot\dfrac12\cdot\left(-\dfrac12\right)\cdot\left(-\dfrac32\right)=\dfrac32>0$ (stijgend).
- Bij $x=\dfrac32$: $\dfrac{\dd f}{\dd x}=4\cdot\dfrac32\cdot\dfrac12\cdot\left(-\dfrac12\right)=-\dfrac32<0$ (dalend).
- Bij $x=3$: $\dfrac{\dd f}{\dd x}=4\cdot3\cdot2\cdot1=24>0$ (stijgend).

Het **tekenschema** is:

| $x$ | $x<0$ | $x=0$ | $0<x<1$ | $x=1$ | $1<x<2$ | $x=2$ | $x>2$ |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| $\dfrac{\dd f}{\dd x}$ | $-$ | $0$ | $+$ | $0$ | $-$ | $0$ | $+$ |
| Verloop van $f$ | Dalend | Lokaal minimum | Stijgend | Lokaal maximum | Dalend | Lokaal minimum | Stijgend |

Bij $x=0$ en $x=2$ verandert de afgeleide van **negatief naar positief**: twee lokale minima.

Bij $x=1$ verandert de afgeleide van **positief naar negatief**: een lokaal maximum.

Bereken de functiewaarden:

$$
\begin{align*}
f(0)&=0^4-4\cdot0^3+4\cdot0^2-3\\
&=-3
\end{align*}
$$

$$
\begin{align*}
f(1)&=1^4-4\cdot1^3+4\cdot1^2-3\\
&=1-4+4-3\\
&=-2
\end{align*}
$$

$$
\begin{align*}
f(2)&=2^4-4\cdot2^3+4\cdot2^2-3\\
&=16-32+16-3\\
&=-3
\end{align*}
$$

Dus de lokale minima liggen in:

$$
\boxed{(0,-3)\quad\text{en}\quad(2,-3)}
$$

Het lokale maximum ligt in:

$$
\boxed{(1,-2)}
$$

```
````

````{admonition} Oefening 3
:class: important, dropdown

Gegeven is de functie:

$$
f(x)=-x^4+4x^3+2x^2-12x+1
$$

Bepaal met behulp van de afgeleide en een tekenschema alle lokale minima en maxima. Bereken ook de coördinaten.

```{dropdown} Uitwerking

We bepalen eerst de afgeleide:

$$
\dfrac{\dd f}{\dd x}=-4x^3+12x^2+4x-12
$$

Stel de afgeleide gelijk aan nul:

$$
\begin{align*}
-4x^3+12x^2+4x-12&=0\\
-4(x^3-3x^2-x+3)&=0\\
-4\bigl(x^2(x-3)-(x-3)\bigr)&=0\\
-4(x^2-1)(x-3)&=0\\
-4(x+1)(x-1)(x-3)&=0\\
x&=-1\quad\text{of}\quad x=1\quad\text{of}\quad x=3
\end{align*}
$$

We onderzoeken het teken van de afgeleide op de vier intervallen:

- Bij $x=-2$: $\dfrac{\dd f}{\dd x}=-4(-2+1)(-2-1)(-2-3)=60>0$ (stijgend).
- Bij $x=0$: $\dfrac{\dd f}{\dd x}=-4(0+1)(0-1)(0-3)=-12<0$ (dalend).
- Bij $x=2$: $\dfrac{\dd f}{\dd x}=-4(2+1)(2-1)(2-3)=12>0$ (stijgend).
- Bij $x=4$: $\dfrac{\dd f}{\dd x}=-4(4+1)(4-1)(4-3)=-60<0$ (dalend).

Het **tekenschema** is:

| $x$ | $x<-1$ | $x=-1$ | $-1<x<1$ | $x=1$ | $1<x<3$ | $x=3$ | $x>3$ |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| $\dfrac{\dd f}{\dd x}$ | $+$ | $0$ | $-$ | $0$ | $+$ | $0$ | $-$ |
| Verloop van $f$ | Stijgend | Lokaal maximum | Dalend | Lokaal minimum | Stijgend | Lokaal maximum | Dalend |

Bij $x=-1$ en $x=3$ verandert de afgeleide van **positief naar negatief**: twee lokale maxima.

Bij $x=1$ verandert de afgeleide van **negatief naar positief**: een lokaal minimum.

Bereken de functiewaarden:

$$
\begin{align*}
f(-1)&=-(-1)^4+4(-1)^3+2(-1)^2-12(-1)+1\\
&=-1-4+2+12+1\\
&=10
\end{align*}
$$

$$
\begin{align*}
f(1)&=-1^4+4\cdot1^3+2\cdot1^2-12\cdot1+1\\
&=-1+4+2-12+1\\
&=-6
\end{align*}
$$

$$
\begin{align*}
f(3)&=-3^4+4\cdot3^3+2\cdot3^2-12\cdot3+1\\
&=-81+108+18-36+1\\
&=10
\end{align*}
$$

Dus de lokale maxima liggen in:

$$
\boxed{(-1,10)\quad\text{en}\quad(3,10)}
$$

Het lokale minimum ligt in:

$$
\boxed{(1,-6)}
$$

```
````
