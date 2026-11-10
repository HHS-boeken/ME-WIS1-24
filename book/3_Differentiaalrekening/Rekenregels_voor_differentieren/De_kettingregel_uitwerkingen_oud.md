## 2.1 Uitwerkingen

<hr style="border:2px solid #9EA700">

### Opgave 4.1a

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = (2x-3)^4
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = (2x-3)^4
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= u^4 \\
u(x) &= 2x-3
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= 4u^3 \\
\dfrac{du}{dx} &= 2
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dx} \\
&= 4(u)^3 \cdot 2 \\
&= 8(u)^3
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 8(2x-3)^3
$$

```
````

### Opgave 4.1b

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = e^{3x}
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = e^{3x}
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= e^u \\
u(x) &= 3x
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= e^u \\
\dfrac{du}{dx} &= 3
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dx} \\
&= e^u \cdot 3 \\
&= 3e^u
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 3e^{3x}
$$

```
````

### Opgave 4.1c

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = \cos(4x)
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = \cos(4x)
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= \cos(u) \\
u(x) &= 4x
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= -\sin(u) \\
\dfrac{du}{dx} &= 4
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dx} \\
&= -\sin(u) \cdot 4 \\
&= -4\sin(u)
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = -4\sin(4x)
$$

```
````

### Opgave 4.1d

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = \ln(4x-5)
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = \ln(4x-5)
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= \ln(u) \\
u(x) &= 4x-5
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= \dfrac{1}{u} \\
\dfrac{du}{dx} &= 4
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dx} \\
&= \dfrac{1}{u} \cdot 4 \\
&= \dfrac{4}{u}
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = \dfrac{4}{4x-5}
$$

```
````

### Opgave 4.1e

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = 5^{3x-2}
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = 5^{3x-2}
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= 5^u \\
u(x) &= 3x-2
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= 5^u \ln(5) \\
\dfrac{du}{dx} &= 3
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dx} \\
&= 5^u \ln(5) \cdot 3 \\
&= 3 \cdot 5^u \ln(5)
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 3 \cdot 5^{3x-2} \ln(5)
$$

```
````

### Opgave 4.1f

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = (x^2+3x)^5
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = (x^2+3x)^5
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= u^5 \\
u(x) &= x^2+3x
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= 5u^4 \\
\dfrac{du}{dx} &= 2x+3
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dx} \\
&= 5(u)^4 \cdot (2x+3) \\
&= 5(2x+3)(u)^4
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 5(2x+3)(x^2+3x)^4
$$

```
````

### Opgave 4.1g

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = e^{x^3}
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = e^{x^3}
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= e^u \\
u(x) &= x^3
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= e^u \\
\dfrac{du}{dx} &= 3x^2
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dx} \\
&= e^u \cdot 3x^2 \\
&= 3x^2e^u
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 3x^2e^{x^3}
$$

```
````

### Opgave 4.1h

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = \sin(x^2+1)
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = \sin(x^2+1)
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= \sin(u) \\
u(x) &= x^2+1
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= \cos(u) \\
\dfrac{du}{dx} &= 2x
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dx} \\
&= \cos(u) \cdot 2x \\
&= 2x\cos(u)
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 2x\cos(x^2+1)
$$

```
````

### Opgave 4.1i

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = 3^{x^2}
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = 3^{x^2}
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= 3^u \\
u(x) &= x^2
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= 3^u \ln(3) \\
\dfrac{du}{dx} &= 2x
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dx} \\
&= 3^u \ln(3) \cdot 2x \\
&= 2x \cdot 3^u \ln(3)
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 2x \cdot 3^{x^2} \ln(3)
$$

```
````

### Opgave 4.1j

````{admonition} Opgave Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = \ln(7x^2+5)
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = \ln(7x^2+5)
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= \ln(u) \\
u(x) &= 7x^2+5
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= \dfrac{1}{u} \\
\dfrac{du}{dx} &= 14x
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dx} \\
&= \dfrac{1}{u} \cdot 14x \\
&= \dfrac{14x}{u}
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = \dfrac{14x}{7x^2+5}
$$

```
````

### Opgave 4.1k

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
    f(x) = \sin^2\left( x^3-3 \right)
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = \sin^2\left( x^3-3 \right)
$$

Kies de buitenste functie $f(u)$ en de binnenste functies $u(v)$ en $v(x)$ :

$$
\begin{align*}
f(u) &= u^2 \\
u(v) &= \sin(v) \\
v(x) &= x^3-3 \\
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(v)$ en $v(x)$::

$$
\begin{align*}
\dfrac{df}{du} &= 2u \\
\dfrac{du}{dv} &= \cos(v) \\
\dfrac{du}{dx} &= 3x^2
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx}  &= \dfrac{df}{du} \cdot \dfrac{du}{dv} \cdot \dfrac{dv}{dx} \\
                &= 2u \cdot \cos(v) \cdot 3x^2 \\
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 2 \sin(v) \cdot \cos(v) \cdot 3x^2
$$

$v$ invullen geeft:

$$
    \dfrac{df}{dx} &=2 \sin( x^3-3 ) \cdot \cos(x^3-3) \cdot 3x^2 \\
    \dfrac{df}{dx} &=6 \sin( x^3-3 ) \cdot \cos(x^3-3) \cdot x^2
$$
```
````

### Opgave 4.1l

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
 f(x) = 4^{(x^2+3x)^2}
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = 4^{(x^2+3x)^2}
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(v)$ en $v(x)$ :

$$
\begin{align*}
f(u) &= 4^u \\
u(v) &= (v)^2 \\
v(x) &= x^2+3x
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(v)$ en $v(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= 4^u \ln(4) \\
\dfrac{du}{dv} &= 2v \\
\dfrac{dv}{dx} &= 2x+3
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dv}  \cdot \dfrac{dv}{dx} \\
&= 4^u \ln(4) \cdot 2v \cdot  (2x+3)\\
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 4^{v^2} \ln(4) \cdot 2v \cdot  (2x+3)\\
$$

$v$ invullen geeft:

$$
    \dfrac{df}{dx} = 2(x^2+3x) \cdot (2x+3) \cdot 4^{(x^2+3x)^2} \ln(4)
$$

```
````

### Opgave 4.1m

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = \log(4x^3+2x)
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = \log(4x^3+2x)
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(x)$ :

$$
\begin{align*}
f(u) &= \log(u) \\
u(x) &= 4x^3+2x
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= \dfrac{1}{u \ln(10)} \\
\dfrac{du}{dx} &= 12x^2+2
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dx} \\
&= \dfrac{1}{u \ln(10)} \cdot (12x^2+2) \\
&= \dfrac{12x^2+2}{u \ln(10)}
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = \dfrac{12x^2+2}{(4x^3+2x) \ln(10)}
$$

```
````

### Opgave 4.1n

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
 f(x) = \cos^3 \left( x-2 \right)
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = \cos^3 \left( x-2 \right)
$$

Kies de buitenste functie $f(u)$ en de binnenste functies $u(v)$ en $v(x)$ :


$$
\begin{align*}
f(u) &= u^3 \\
u(v) &= \cos(v) \\
v(x) &= x-2
\end{align*}
$$

Differentieer de functies $f(u)$ en $u(v)$ en $v(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= 3u^2 \\
\dfrac{du}{dv} &= -\sin(v) \\
\dfrac{dv}{dx} &= 1
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dv} \cdot \cdot \dfrac{dv}{dx}  \\
&= -3u^2 \cdot -\sin(v) \cdot 1
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = -3 \cos^2(v) \cdot -\sin(v) \cdot 1
$$

$v$ invullen geeft:

$$
    \dfrac{df}{dx} = -3\cos^2\left( x-2 \right)\sin\left( x-2 \right)
$$

```
````

### Opgave 4.1o

````{admonition} Antwoord
:class: important, dropdown

Bepaal de afgeleide van de volgende functie.

$$
f(x) = \ln^3(2x^2+5)
$$

```{dropdown} Uitwerking

Bepaal de afgeleide van de volgende functie:

$$
    f(x) = \ln^3(2x^2+5)
$$

Kies de buitenste functie $f(u)$ en de binnenste functie $u(v)$ en $v(x)$:

$$
\begin{align*}
f(u) &= u^3 \\
u(v) &= \ln(v)\\
v(x) &= 2x^2+5
\end{align*}
$$

Differentieer de functies $f(u)$, $u(v)$ en $v(x)$:

$$
\begin{align*}
\dfrac{df}{du} &= 3u^2 \\
\dfrac{du}{dv} &= \dfrac{1}{v} \\
\dfrac{dv}{dx} &= 4x
\end{align*}
$$

Toepassen van de kettingregel:

$$
\begin{align*}
\dfrac{df}{dx} &= \dfrac{df}{du} \cdot \dfrac{du}{dv} \cdot \dfrac{dv}{dx}  \\
&= 3u^2 \cdot \dfrac{1}{v} \cdot 4x \\
\end{align*}
$$

$u$ invullen geeft:

$$
    \dfrac{df}{dx} = 3\ln^2(v)\cdot \dfrac{1}{v} \cdot 4x \\
$$

$v$ invullen geeft:

$$
    \dfrac{df}{dx} &= 3\ln^2(2x^2+5)\cdot \dfrac{1}{2x^2+5} \cdot 4x \\
    &= 12x\ln^2(2x^2+5)\cdot \dfrac{1}{2x^2+5} \\
    &= \dfrac{12x\ln^2(2x^2+5)}{2x^2+5}
$$

```
````
