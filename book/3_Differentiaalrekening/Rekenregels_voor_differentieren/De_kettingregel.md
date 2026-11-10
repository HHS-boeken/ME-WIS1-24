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
    \dfrac{df}{dx} = \dfrac{df}{du} \cdot \dfrac{du}{dx} 
$$

Dit betekent dat je eerst de **buitenste functie differentieert** en daarna vermenigvuldigt met de **afgeleide van de binnenste functie**.

````

## 2.1.1 De kettingregel

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
\dfrac{df}{du} &= 5u^4 \\
\dfrac{du}{dx} &= 3
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{dx}{du} \\
&= 5(u)^4 \cdot 3 \\
&= 15(u)^4
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 15(3x+2)^4
$$

```

````{admonition} Oefening 1
:class: important, dropdown

Bereken de afgeleide van de volgende functie:

$$
    f(x) = e^{4x}
$$

```{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:

$$
    f(x) = e^{4x}
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= e^u \\
u(x) &= 4x
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= e^u \\
\dfrac{du}{dx} &= 4
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{dx}{du} \\
&= e^u \cdot 4 \\
&= 4e^u
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 4e^{4x}
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
\dfrac{df}{du} &= \cos(u) \\
\dfrac{du}{dx} &= 5
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{dx}{du} \\
&= \cos(u) \cdot 5 \\
&= 5\cos(u)
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 5\cos(5x)
$$

```
````