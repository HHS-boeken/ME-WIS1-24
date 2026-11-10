# 4.2 De productregel

````{admonition} Theorie
:class: tip, dropdown open

De **productregel** is een afgeleide regel die wordt gebruikt bij het differentiëren van een functie die het product is van twee differentieerbare functies. Als een functie  $f(x)$ bestaat uit het product van twee functies $u(x)$ en $v(x)$, dan geldt:

\begin{align*}
  f(x) = u(x) \cdot v(x)
\end{align*}

De afgeleide van $f(x)$ wordt dan gegeven door:

\begin{align*}
  \dfrac{df(x)}{dx} = \dfrac{du(x)}{dx} \cdot v(x) + u(x) \cdot \dfrac{dv(x)}{dx}
\end{align*}

Dit betekent dat je eerst de afgeleide van de eerste functie neemt en deze vermenigvuldigt met de tweede functie, en daarna de eerste functie vermenigvuldigt met de afgeleide van de tweede functie.

````{admonition} Standaard afgeleiden
:class: warning

| Functie $f(x)$ | Afgeleide $\dfrac{df(x)}{dx}$ |
|--------------------|-------------------|
| \( c \) (constante) | $0$ |
| $x^n$ | $n x^{n-1}$ |
| $e^x$ | $e^x$ |
| $a^x$ | $a^x \ln a$ |
| $\ln x$ | $\frac{1}{x}$ |
| $^a \log x$  | $\frac{1}{x \ln a}$ |
| $\sin x$ | $\cos x$ |
| $\cos x$ | $-\sin x$ |

````

## 4.2.1 De productregel

:::{admonition} Voorbeeld 1: productregel
:class: dropdown

Bereken de afgeleide van de volgende functie:

$$
  f(x) = {\color{blue} (x^2-4)} {\color{green}(x^3+7x-5)}
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  u &= {\color{blue} (x^2-4)} \\
  v &= {\color{green}(x^3+7x-5)}
\end{align*}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  \dfrac{du}{dx} &=   {\color{blue}2x^2} \\
  \dfrac{dv}{dx} &= {\color{green}3x^2+7}
\end{align*}
$$

Toepassen van de productregel:

$$
\begin{align*}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= {\color{blue} 2x^2} \cdot {\color{green}(x^3+7x-5)} + {\color{blue} (x^2-4)} \cdot {\color{green}(3x^2+7)}
\end{align*}
$$
:::

::::{admonition} Oefening 1
:class: important, dropdown

Bereken de afgeleide van de volgende functie:

$$
  f(x) = e^x(2x^3+x^2+3x)
$$

:::{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:

$$
  f(x) = {\color{blue}e^x}{\color{green}(2x^3+x^2+3x)}
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  u &= {\color{blue}e^x} \\
  v &= {\color{green}(2x^3+x^2+3x)}
\end{align*}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  \dfrac{du}{dx} &= {\color{blue}e^x }\\
  \dfrac{dv}{dx} &= {\color{green}6x^2+2x+3 }
\end{align*}
$$

Toepassen van de productregel:

$$
\begin{align*}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= {\color{blue}e^x} \cdot (2x^3+x^2+3x) + {\color{blue}e^x} \cdot (6x^2+2x+3) \\
  &= e^x \left( (2x^3 + x^2 + 3x) + (6x^2 + 2x + 3) \right) \\
  &= e^x (2x^3 + 7x^2 + 5x + 3 )
\end{align*}
$$

:::
::::

::::{admonition} Oefening 2
:class: important, dropdown

Bereken de afgeleide van de volgende functie:

$$
  f(x) = \ln(x)\cos(x)
$$

:::{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:

$$
  f(x) = {\color{blue}\ln(x)}{\color{green}\cos(x)}
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  u &= {\color{blue}\ln(x)} \\
  v &= {\color{green}\cos(x)}
\end{align*}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  \dfrac{du}{dx} &= {\color{blue}\dfrac{1}{x}} \\
  \dfrac{dv}{dx} &= {\color{green}-\sin(x)}
\end{align*}
$$

Toepassen van de productregel:

$$
\begin{align*}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= {\color{blue}\dfrac{1}{x}} \cdot {\color{green}\cos(x)} + {\color{blue}\ln(x)} \cdot {\color{green}-\sin(x)} \\
  &= \dfrac{\cos(x)}{x} - \ln(x)\sin(x)
\end{align*}
$$

:::
::::

## 4.2.2 De productregel + kettingregel

:::{admonition} Voorbeeld 2: productregel + kettingregel
:class: dropdown

Bereken de afgeleide van de volgende functie:

$$
  f(x) = {\color{blue}\sin(7x)}{\color{green}(3x-1)^4}
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  u &= {\color{blue}\sin(7x)} \\
  v &= {\color{green}(3x-1)^4}
\end{align*}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  \dfrac{du}{dx} &= {\color{blue}7\cos(7x) }\\
  \dfrac{dv}{dx} &= {\color{green}4 \cdot (3x-1)^3 \cdot 3} \\
  &={\color{green}12(3x-1)^3}
\end{align*}
$$

Toepassen van de productregel:

$$
\begin{align*}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= {\color{blue}7\cos(7x)} \cdot {\color{green}(3x-1)^4} + {\color{blue}\sin(7x)} \cdot {\color{green}12(3x-1)^3}
\end{align*}
$$

:::

::::{admonition} Oefening 3
:class: important, dropdown

Bereken de afgeleide van de volgende functie:

$$
  f(x) = -5e^{-4x}4^{2x}
$$

:::{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:

$$
  f(x) = {\color{blue}-5e^{-4x}}{\color{green}4^{2x}}
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  u &= {\color{blue}-5e^{-4x} }\\
  v &= {\color{green}4^{2x} }
\end{align*}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  \dfrac{du}{dx} &= {\color{blue}-5e^{-4x} \cdot -4} \\
  &= {\color{blue}20e^{-4x} }\\
  \dfrac{dv}{dx} &= {\color{green}4^{2x} \cdot \ln(4) \cdot 2}
\end{align*}
$$

Toepassen van de productregel:

$$
\begin{align*}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= {\color{blue}20e^{-4x}} \cdot {\color{green}4^{2x}} + {\color{blue}-5e^{-4x}} \cdot  {\color{green}4^{2x} \cdot \ln(4) \cdot 2} \\
   &= -5e^{-4x} \cdot 4^{2x}  ( -4 + 2 \ln(4))
\end{align*}
$$

:::
::::

::::{admonition} Oefening 4
:class: important, dropdown

Bereken de afgeleide van de volgende functie:

$$
  f(x) =  \log(4x-3) \sqrt{x^2-6}
$$

:::{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:

$$
  f(x) = {\color{blue}\log(4x-3)}{\color{green} \sqrt{x^2-6}}
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  u &= {\color{blue}\log(4x-3) }\\
  v &= {\color{green}\sqrt{x^2-6} }\\
  &=  {\color{green}(x^2-6)^{\frac{1}{2}}}
\end{align*}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
\begin{align*}
  \dfrac{du}{dx} &= {\color{blue}\dfrac{1}{(4x-3) \ln(10)} \cdot 4} \\
  &= {\color{blue}\dfrac{4}{(4x-3) \ln(10)} }\\
  \dfrac{dv}{dx} &= {\color{green}\dfrac{1}{2}(x^2 -6)^{-\frac{1}{2}} \cdot 2x }\\
  &= {\color{green}\dfrac{x}{ \sqrt{x^2-6} }}
\end{align*}
$$

Toepassen van de productregel:

$$
\begin{align*}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= {\color{blue}\dfrac{4}{(4x-3) \ln(10)}} \cdot {\color{green}\sqrt{x^2-6}} + {\color{blue}\log(4x-3)} \cdot {\color{green}\dfrac{x}{ \sqrt{x^2-6} }} \\
  &= \dfrac{4\sqrt{x^2-6}}{(4x-3) \ln(10)}  + \dfrac{x\log(4x-3)}{ \sqrt{x^2-6} }
\end{align*}
$$

:::
::::
