# 2.1 De kettingregel

````{admonition} Theorie
:class: tip, dropdown open

De **kettingregel** wordt gebruikt bij het differentiëren van een functie die bestaat uit een **functie van een functie**.

Als een functie bestaat uit een buitenste functie $f(u)$ en een binnenste functie $u(x)$, dan schrijven we:

$$
    f(x) = f(u(x))
$$

De afgeleide van $f(x)$ wordt dan gegeven door:

$$
    \dfrac{\dd f}{\dd x} = \dfrac{\dd f}{\dd u} \cdot \dfrac{\dd u}{\dd x} 
$$

Dit betekent dat je eerst de **buitenste functie differentieert** en daarna vermenigvuldigt met de **afgeleide van de binnenste functie**.

````

## 4.1.1 De kettingregel

```{admonition} Voorbeeld 1: ketttingregel 
:class: dropdown

Bereken de afgeleide van de volgende functie:

$$
    f(x) = (3x+2)^5
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= u^5 \\
u(x) &= 3x+2
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{\dd f}{\dd u} &= 5u^4 \\
\dfrac{\dd u}{\dd x} &= 3
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{\dd f}{\dd x} &= \dfrac{\dd f}{\dd u} \cdot \dfrac{\dd u}{\dd x} \\
&= 5(u)^4 \cdot 3 \\
&= 15(u)^4
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{\dd f}{\dd x} = 15(3x+2)^4
$$

```

````{admonition} Oefening 1
:class: important, dropdown

Bereken de afgeleide van de volgende functie:

$$
    f(x) = \sqrt{x^2+4}
$$

```{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:

$$
    f(x) 
    &= \sqrt{x^2+4}\\
    &= (x^2+4)^\frac{1}{2}
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$:

$$
\begin{align*}
f(u) &= (u)^\frac{1}{2} \\
u(x) &= x^2+4
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{\dd f}{\dd u} &= \dfrac{1}{2} u^{-\frac{1}{2}} \\
\dfrac{\dd u}{\dd x} &= 2x
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{\dd f}{\dd x} &= \dfrac{\dd f}{\dd u} \cdot \dfrac{\dd u}{\dd x} \\
&= \dfrac{1}{2} u^{-\frac{1}{2}}  \cdot 2x \\
&= \dfrac{x}{\sqrt{u}}
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{\dd f}{\dd x} = \dfrac{x}{\sqrt{x^2+4}}
$$

```
````

````{admonition} Oefening 2
:class: important, dropdown

Bereken de afgeleide van de volgende functie:

$$
    f(x) = \sin(5x)
$$

```{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:

$$
    f(x) = \sin(5x)
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= \sin(u) \\
u(x) &= 5x
\end{align*}
$$



Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{\dd f}{\dd u} &= \cos(u) \\
\dfrac{\dd u}{\dd x} &= 5
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{\dd f}{\dd x} &= \dfrac{\dd f}{\dd u} \cdot \dfrac{\dd u}{\dd x} \\
&= \cos(u) \cdot 5 \\
&= 5\cos(u)
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{\dd f}{\dd x} = 5\cos(5x)
$$

```
````