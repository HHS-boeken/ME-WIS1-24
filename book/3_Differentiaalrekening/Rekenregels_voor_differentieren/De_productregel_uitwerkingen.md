
## 4.2 Uitwerkingen

<hr style="border:2px solid #9EA700">

### Opgave 4.2a

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{df}{dx} = 2x e^x + x^2 e^x
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  f(x) = x^2 e^x
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= x^2 \\
  v &= e^x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  \dfrac{du}{dx} &= 2x \\
  \dfrac{dv}{dx} &= e^x
\end{align}
$$


Toepassen van de productregel:

$$
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= 2x e^x + x^2 e^x
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2b

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{dg}{dx} = \cos x - (x+1) \sin x
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  g(x) = (x+1) \cos x
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= (x+1) \\
  v &= \cos x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  \dfrac{du}{dx} &= 1 \\
  \dfrac{dv}{dx} &= -\sin x
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{dg}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= 1 \cdot \cos x + (x+1) \cdot (-\sin x) \\
  &= \cos x - (x+1) \sin x
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2c

::::{admonition} Antwoord
:class: important, dropdown

::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2d

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{dp}{dx} = - (e^x + x^2) \sin x + (e^x + 2x) \cos x
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  p(x) = (e^x + x^2) \cos x
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= e^x + x^2 \\
  v &= \cos x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  \dfrac{du}{dx} &= e^x + 2x \\
  \dfrac{dv}{dx} &= -\sin x
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{dp}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= (e^x + 2x) \cos x + (e^x + x^2)(-\sin x) \\
  &= - (e^x + x^2) \sin x + (e^x + 2x) \cos x
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2e

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{dq}{dx} = 4x^3 \ln x + x^3
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  q(x) = x^4 \ln x
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= x^4 \\
  v &= \ln x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  \dfrac{du}{dx} &= 4x^3 \\
  \dfrac{dv}{dx} &= \dfrac{1}{x}
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{dq}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= 4x^3 \ln x + x^4 \cdot \dfrac{1}{x} \\
  &= 4x^3 \ln x + x^3
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2f

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{df}{dx} = (8x^3 + 6x^2 + 12x + 3)e^{4x}
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  f(x) = (2x^3 + 3x) e^{4x}
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= 2x^3 + 3x \\
  v &= e^{4x}
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  \dfrac{du}{dx} &= 6x^2 + 3 \\
  \dfrac{dv}{dx} &= 4e^{4x}
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= (6x^2 + 3)e^{4x} + (2x^3 + 3x)(4e^{4x}) \\
  &= (6x^2 + 3)e^{4x} + 4(2x^3 + 3x)e^{4x} \\
  &= (6x^2 + 3 + 8x^3 + 12x)e^{4x} \\
  &= (8x^3 + 6x^2 + 12x + 3)e^{4x}
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2g

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{dg}{dx} = 2x \ln x + \dfrac{x^2 + 1}{x}
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  g(x) = (x^2 + 1) \ln x
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= x^2 + 1 \\
  v &= \ln x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  \dfrac{du}{dx} &= 2x \\
  \dfrac{dv}{dx} &= \dfrac{1}{x}
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{dg}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= 2x \ln x + (x^2 + 1) \cdot \dfrac{1}{x} \\
  &= 2x \ln x + \dfrac{x^2 + 1}{x}
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2h

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{dh}{dx} = (x^4 + 4x^3 - 2x^2 - 4x)e^x
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  h(x) = (x^4 - 2x^2) e^x
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= x^4 - 2x^2 \\
  v &= e^x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  \dfrac{du}{dx} &= 4x^3 - 4x \\
  \dfrac{dv}{dx} &= e^x
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{dh}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= (4x^3 - 4x)e^x + (x^4 - 2x^2)e^x \\
  &= (4x^3 - 4x + x^4 - 2x^2)e^x \\
  &= (x^4 + 4x^3 - 2x^2 - 4x)e^x
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2i

::::{admonition} Antwoord


::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2j

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{dq}{dx} = e^x\left(\frac{1}{x} + \ln x + 2x + x^2\right)
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  q(x) = (\ln x + x^2)e^x
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= \ln x + x^2 \\
  v &= e^x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  \dfrac{du}{dx} &= \dfrac{1}{x} + 2x \\
  \dfrac{dv}{dx} &= e^x
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{dq}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= \left(\dfrac{1}{x} + 2x\right)e^x + (\ln x + x^2)e^x \\
  &= e^x\left(\dfrac{1}{x} + 2x + \ln x + x^2\right)
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2k

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{df}{dx} = \left(3x^2 + e^x\right) \ln x + \frac{x^3 + e^x}{x}
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  f(x) = (x^3 + e^x)(\ln x)
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= x^3 + e^x \\
  v &= \ln x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  \dfrac{du}{dx} &= 3x^2 + e^x \\
  \dfrac{dv}{dx} &= \dfrac{1}{x}
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= (3x^2 + e^x) \ln x + (x^3 + e^x) \cdot \dfrac{1}{x} \\
  &= (3x^2 + e^x) \ln x + \frac{x^3 + e^x}{x}
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2l

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{dy}{dt} = e^{-\alpha t} (-\alpha \cos(\omega t) - \omega \sin(\omega t))
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  y(t) = e^{-\alpha t} \cos(\omega t)
$$

Kies de functies $u(t)$ en $v(t)$:

$$
\begin{align}
  u &= e^{-\alpha t} \\
  v &= \cos(\omega t)
\end{align}
$$

Differentieer de functies $u(t)$ en $v(t)$:

$$
\begin{align}
  \dfrac{du}{dt} &= -\alpha e^{-\alpha t} \\
  \dfrac{dv}{dt} &= -\omega \sin(\omega t)
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{dy}{dt} = \dfrac{d}{dt}(u \cdot v) &= \dfrac{du}{dt} \cdot v + u \cdot \dfrac{dv}{dt} \\
  &= (-\alpha e^{-\alpha t}) \cos(\omega t) + e^{-\alpha t} (-\omega \sin(\omega t)) \\
  &= -\alpha e^{-\alpha t} \cos(\omega t) - \omega e^{-\alpha t} \sin(\omega t) \\
  &= e^{-\alpha t} (-\alpha \cos(\omega t) - \omega \sin(\omega t))
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2m

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{df}{dx} = (\frac{1}{x} + e^x)(\cos x + x) + (\ln x + e^x)(1 - \sin x)
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  f(x) = (\ln x + e^x)(\cos x + x)
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= \ln x + e^x \\
  v &= \cos x + x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  \dfrac{du}{dx} &= \frac{1}{x} + e^x \\
  \dfrac{dv}{dx} &= -\sin x + 1
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= (\frac{1}{x} + e^x)(\cos x + x) + (\ln x + e^x)(- \sin x + 1) \\
  &= (\frac{1}{x} + e^x)(\cos x + x) + (\ln x + e^x)(1 - \sin x)
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2n

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{dz}{dt} = (2t - t^2 - 1)e^{-t}
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  z(t) = (t^2 + 1) e^{-t}
$$

Kies de functies $u(t)$ en $v(t)$:

$$
\begin{align}
  u &= t^2 + 1 \\
  v &= e^{-t}
\end{align}
$$

Differentieer de functies $u(t)$ en $v(t)$:

$$
\begin{align}
  \dfrac{du}{dt} &= 2t \\
  \dfrac{dv}{dt} &= -e^{-t}
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{dz}{dt} = \dfrac{d}{dt}(u \cdot v) &= \dfrac{du}{dt} \cdot v + u \cdot \dfrac{dv}{dt} \\
  &= (2t e^{-t}) + (t^2 + 1)(-e^{-t}) \\
  &= (2t e^{-t} - (t^2 + 1) e^{-t}) \\
  &= (2t - t^2 - 1)e^{-t}
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.2o

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{dw}{dt} = \left( -e^{-t} + \frac{1}{t+1} \right) \cos (\omega t) - \omega (e^{-t} + \ln (t+1)) \sin (\omega t)
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  v(t) = (e^{-t} + \ln (t+1)) \cos (\omega t)
$$

Kies de functies $u(t)$ en $v(t)$:

$$
\begin{align}
  u &= e^{-t} + \ln (t+1) \\
  v &= \cos (\omega t)
\end{align}
$$

Differentieer de functies $u(t)$ en $v(t)$:

$$
\begin{align}
  \dfrac{du}{dt} &= -e^{-t} + \frac{1}{t+1} \\
  \dfrac{dv}{dt} &= -\omega \sin (\omega t)
\end{align}
$$

Toepassen van de productregel:

$$
\begin{align}
  \dfrac{dw}{dt} = \dfrac{d}{dt}(u \cdot v) &= \dfrac{du}{dt} \cdot v + u \cdot \dfrac{dv}{dt} \\
  &= (-e^{-t} + \frac{1}{t+1}) \cos (\omega t) + (e^{-t} + \ln (t+1)) (-\omega \sin (\omega t)) \\
  &= \left( -e^{-t} + \frac{1}{t+1} \right) \cos (\omega t) - \omega (e^{-t} + \ln (t+1)) \sin (\omega t)
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">
