## 4.3 Uitwerkingen

<hr style="border:2px solid #9EA700">

### Opgave 4.3a

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{df}{dx} = \frac{  xe^x }{ (x + 1)^2}
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  f(x) =  \dfrac{e^x}{x+1}
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= e^x \\
  v &= x + 1\\
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
  \dfrac{du}{dx} &= e^x \\
  \dfrac{dv}{dx} &= 1
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (x + 1) \cdot e^x - e^x \cdot  1 }{ (x + 1)^2} \\
  &= \frac{  xe^x }{ (x + 1)^2}
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3b

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{df}{dx} = \frac{  x(1-2\ln(x)) }{ x ^4 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  f(x) =  \dfrac{ \ln(x) }{ x^2 }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= \ln(x) \\
  v &= x^2\\
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
  \dfrac{du}{dx} &= \dfrac{1}{x} \\
  \dfrac{dv}{dx} &= 2x
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ x^2 \cdot \dfrac{1}{x}  - \ln(x)  \cdot  2x }{ (x^2)^2} \\
  &= \frac{  x(1-2\ln(x)) }{ x ^4 } \\
    &= \frac{  (1-2\ln(x)) }{ x ^3 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">


### Opgave 4.3c

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{df}{dx} = \frac{  (x+2) \cdot \cos(x)  - \sin(x) }{ (x+2)^2 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  f(x) =  \dfrac{ \sin(x) }{ x+2 }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= \sin(x) \\
  v &= x+2\\
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
  \dfrac{du}{dx} &= \cos(x) \\
  \dfrac{dv}{dx} &= 1
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (x+2) \cdot \cos(x)  - \sin(x)  \cdot 1 }{ (x+2)^2} \\
  &= \frac{  (x+2) \cdot \cos(x)  - \sin(x) }{ (x+2)^2 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3d

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  2x - x^2 }{ e^x }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ x^2 }{ e^x }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= x^2 \\
v &= e^x\
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= 2x \\
\dfrac{dv}{dx} &= e^x
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ e^x \cdot 2x - x^2 \cdot e^x }{ (e^x)^2} \\
&= \frac{ e^x(2x-x^2) }{ e^{2x} } \\
&= \frac{ 2x-x^2 }{ e^x }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3e

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  -1-e^x+e^x(x-1) }{ (x-1)^2 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ x + e^x }{ x-1 }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= x + e^x \\
v &= x-1
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= 1 + e^x \\
\dfrac{dv}{dx} &= 1
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ (x-1) \cdot (1+e^x) - (x+e^x) \cdot 1 }{ (x-1)^2} \\
&= \frac{ x-1 + e^x(x-1) - x - e^x }{ (x-1)^2} \\
&= \frac{ -1-e^x+e^x(x-1) }{ (x-1)^2 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3f

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  -\ln(x)\sin(x) - \dfrac{\cos(x)}{x} }{ (\ln(x))^2 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ \cos(x) }{ \ln(x) }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= \cos(x) \\
v &= \ln(x)
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= -\sin(x) \\
\dfrac{dv}{dx} &= \dfrac{1}{x}
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ \ln(x) \cdot (-\sin(x)) - \cos(x) \cdot \dfrac{1}{x} }{ (\ln(x))^2} \\
&= \frac{  -\ln(x)\sin(x) - \dfrac{\cos(x)}{x} }{ (\ln(x))^2 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3g

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  (e^x+x)(2x+4) - (x^2+4x+3)(e^x+1) }{ (e^x+x)^2 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ x^2 + 4x + 3 }{ e^x + x }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= x^2 + 4x + 3 \\
v &= e^x + x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= 2x + 4 \\
\dfrac{dv}{dx} &= e^x + 1
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ (e^x+x) \cdot (2x+4) - (x^2+4x+3) \cdot (e^x+1) }{ (e^x+x)^2} \\
&= \frac{  (e^x+x)(2x+4) - (x^2+4x+3)(e^x+1) }{ (e^x+x)^2 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3h

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  2x e^{x^2}(x+1) - e^{x^2} }{ (x+1)^2 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ e^{x^2} }{ x+1 }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= e^{x^2} \\
v &= x+1
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= 2x e^{x^2} \\
\dfrac{dv}{dx} &= 1
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ (x+1) \cdot 2x e^{x^2} - e^{x^2} \cdot 1 }{ (x+1)^2} \\
&= \frac{  2x e^{x^2}(x+1) - e^{x^2} }{ (x+1)^2 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3i

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  \dfrac{2x^2}{x^2+1} - 3\ln(x^2+1) }{ x^4 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ \ln(x^2 + 1) }{ x^3 }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= \ln(x^2 + 1) \\
v &= x^3
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= \dfrac{2x}{x^2+1} \\
\dfrac{dv}{dx} &= 3x^2
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ x^3 \cdot \dfrac{2x}{x^2+1} - \ln(x^2+1) \cdot 3x^2 }{ (x^3)^2} \\
&= \frac{  \dfrac{2x^4}{x^2+1} - 3x^2\ln(x^2+1) }{ x^6 } \\
&= \frac{  \dfrac{2x^2}{x^2+1} - 3\ln(x^2+1) }{ x^4 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3j

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  2 x\cos(x^2) - \sin(x^2) }{ e^{x} }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ \sin(x^2) }{ e^x }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= \sin(x^2) \\
v &= e^x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= 2x\cos(x^2) \\
\dfrac{dv}{dx} &= e^x
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ e^x \cdot 2x\cos(x^2) - \sin(x^2) \cdot e^x }{ (e^x)^2} \\
&= \frac{  2e^x x\cos(x^2) - e^x\sin(x^2) }{ e^{2x} } \\
&= \frac{  2 x\cos(x^2) - \sin(x^2) }{ e^{x} }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3k

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  2x\sqrt{x^2+1} - \dfrac{x(x^2+3)}{\sqrt{x^2+1}} }{ x^2+1 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ x^2 + 3 }{ \sqrt{x^2 + 1} }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= x^2 + 3 \\
v &= \sqrt{x^2 + 1} \\
    &= (x^2 + 1)^{\frac{1}{2}}
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= 2x \\
\dfrac{dv}{dx} &= \frac{1}{2} \cdot 2x \cdot (x^2 + 1)^{-\frac{1}{2}} \\
 &= x \cdot (x^2 + 1)^{-\frac{1}{2}}
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ \sqrt{x^2+1} \cdot 2x - (x^2+3) \cdot \dfrac{x}{\sqrt{x^2+1}} }{ (\sqrt{x^2+1})^2} \\
&= \frac{  2x\sqrt{x^2+1} - \dfrac{x(x^2+3)}{\sqrt{x^2+1}} }{ x^2+1 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3l

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  \cos(x)(e^x+3x^2) + (e^x+x^3)\sin(x) }{ \cos^2(x) }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ e^x + x^3 }{ \cos(x) }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= e^x + x^3 \\
v &= \cos(x)
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= e^x + 3x^2 \\
\dfrac{dv}{dx} &= -\sin(x)
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ \cos(x) \cdot (e^x+3x^2) - (e^x+x^3) \cdot (-\sin(x)) }{ \cos^2(x)} \\
&= \frac{  \cos(x)(e^x+3x^2) + (e^x+x^3)\sin(x) }{ \cos^2(x) }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3m

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  (x^2-4)(1+e^{\sin(x)}\cos(x)) - (x+e^{\sin(x)})\cdot 2x }{ (x^2-4)^2 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ x + e^{\sin(x)} }{ x^2-4 }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= x + e^{\sin(x)} \\
v &= x^2-4
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= 1+e^{\sin(x)}\cos(x) \\
\dfrac{dv}{dx} &= 2x
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ (x^2-4) \cdot (1+e^{\sin(x)}\cos(x)) - (x+e^{\sin(x)}) \cdot 2x }{ (x^2-4)^2} \\
&= \frac{  (x^2-4)(1+e^{\sin(x)}\cos(x)) - (x+e^{\sin(x)})\cdot 2x }{ (x^2-4)^2 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3n

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  -e^x\tan(x) - e^x\ln(\cos(x)) }{ e^{2x} }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ \ln(\cos(x)) }{ e^x }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= \ln(\cos(x)) \\
v &= e^x
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= -\tan(x) \\
\dfrac{dv}{dx} &= e^x
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ e^x \cdot (-\tan(x)) - \ln(\cos(x)) \cdot e^x }{ (e^x)^2} \\
&= \frac{  -e^x\tan(x) - e^x\ln(\cos(x)) }{ e^{2x} }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3o

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  x^4 \cdot \dfrac{3x^2}{2\sqrt{x^3+2}} - \sqrt{x^3+2} \cdot 4x^3 }{ x^8 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ \sqrt{x^3+2} }{ x^4 }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= \sqrt{x^3+2} \\
&= (x^3+2)^{\frac{1}{2}}
v &= x^4\
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= (x^3+2)^{-\frac{1}{2}} \cdot \dfrac{1}{2} \cdot 3x^2\\
                &= (x^3+2)^{-\frac{1}{2}} \cdot \dfrac{3}{2}x^2\\
\dfrac{dv}{dx} &= 4x^3
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ x^4 \cdot \dfrac{3x^2}{2\sqrt{x^3+2}} - \sqrt{x^3+2} \cdot 4x^3 }{ (x^4)^2} \\
&= \frac{  x^4 \cdot \dfrac{3x^2}{2\sqrt{x^3+2}} - \sqrt{x^3+2} \cdot 4x^3 }{ x^8 } \\
&= \frac{  x \cdot \dfrac{3x^2}{2\sqrt{x^3+2}} - \sqrt{x^3+2} \cdot 4 }{ x^5 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3p

::::{admonition} Antwoord
:class: important, dropdown

$$
\dfrac{df}{dx} = \frac{  \ln(x+1) \cdot 2\sin(x)\cos(x) - \sin^2(x) \cdot \dfrac{1}{x+1} }{ (\ln(x+1))^2 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
f(x) =  \dfrac{ \sin^2(x) }{ \ln(x+1) }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
u &= \sin^2(x) \\
v &= \ln(x+1)
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\dfrac{du}{dx} &= 2\sin(x)\cos(x) \\
\dfrac{dv}{dx} &= \dfrac{1}{x+1}
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
\dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
&= \frac{ \ln(x+1) \cdot 2\sin(x)\cos(x) - \sin^2(x) \cdot \dfrac{1}{x+1} }{ (\ln(x+1))^2} \\
&= \frac{  \ln(x+1) \cdot 2\sin(x)\cos(x) - \sin^2(x) \cdot \dfrac{1}{x+1} }{ (\ln(x+1))^2 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">
