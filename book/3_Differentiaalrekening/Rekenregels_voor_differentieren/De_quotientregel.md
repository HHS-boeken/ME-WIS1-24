# 4.3 De quotiëntregel

````{admonition} Theorie
:class: tip, dropdown open

De **quotiëntregel** is een afgeleide regel die wordt gebruikt bij het differentiëren van een functie die een quotiënt (breuk) is van twee differentieerbare functies. Als een functie $f(x)$ geschreven kan worden als een quotiënt van $u(x)$ en $v(x)$, dan geldt:

\begin{align*}
    f(x) = \frac{u(x)}{v(x)}
\end{align*}

De afgeleide van $f(x)$ wordt dan gegeven door:

\begin{align*}
    \dfrac{df(x)}{dx} = \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2}
\end{align*}

Dit betekent dat je eerst de noemer neemt deze vermenigvuldigt met afgeleide van de teller, daarna de teller vermenigvuldigt met de afgeleide van de noemer, en vervolgens het verschil deelt door het kwadraat van de noemer.

````{admonition} Ezelsbruggetje voor de quotiëntregel
:class: warning

$\dfrac{N\cdot AT - T \cdot AN}{N^2}$

Noemer $\cdot$ Afgeleide van de Teller - Teller $\cdot$ Afgeleide van de Noemer gedeelt door noemer$^2$

````

## 4.3.1 De quotiëntregel

```{admonition} Voorbeeld 1: quotiëntregel
:class: dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{x^2}{x+1}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= x^2 \\
  v &= x+1 \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= 2x \\
  \dfrac{dv}{dx} &= 1
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (x + 1) \cdot 2x - x^2 \cdot  1 }{ (x + 1)^2} \\
  &= \frac{ 2x^2 + 2x - x^2 }{ (x + 1)^2} \\
  &= \frac{ x^2 + 2x }{ (x + 1)^2} \\
\end{align}

```

````{admonition} Oefening 1
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{e^x}{x^2+5}
\end{align*}

```{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{e^x}{x^2+5}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= e^x \\
  v &= x^2+5 \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= e^x \\
  \dfrac{dv}{dx} &= 2x
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (x^2 + 5) \cdot e^x - e^x \cdot  2x }{ (x^2 + 5)^2} \\
  &= \frac{  e^x(x^2 - 2x + 5) }{ (x^2 + 5)^2}
\end{align}


```
````

````{admonition} Oefening 2
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{  \ln(x) } {5 - \cos(x) }
\end{align*}

```{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{  \ln(x) } {5 - \cos(x) }
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= \ln(x) \\
  v &= 5 - \cos(x) \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= \dfrac{1}{x} \\
  \dfrac{dv}{dx} &= \sin(x)
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v \dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (5 - \cos(x)) \cdot \dfrac{1}{x} - \ln(x) \cdot \sin(x) }{ (5 - \cos(x))^2} \\
  &= \frac{ \dfrac{ 5 - \cos(x) }{x} - \sin(x) \ln(x) }{ (5 - \cos(x))^2} \\
\end{align}


```
````

## 4.3.2 De quotiëntregel + kettingregel

````{admonition} Oefening 3
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{ \sin^2(x) }{ \ln(5x+1)}
\end{align*}

```{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{ \sin^2(x) }{ \ln(5x+1)}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &=  \sin^2(x) \\
  v &=  \ln(5x+1) \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= 2 \sin(x)\cos(x) \\
  \dfrac{dv}{dx} &= \dfrac{1}{5x+1} \cdot 5 \\
                &= \dfrac{5}{5x+1} \\
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (\ln(5x+1)) \cdot 2 \sin(x)\cos(x)  - \sin^2(x) \cdot  \dfrac{5}{5x+1} }{ (\ln(5x+1))^2} \\
  &= \frac{ 2 \sin(x)\cos(x)(\ln(5x+1)) - \dfrac{5\sin^2(x)}{5x+1} }{ \ln^2(5x+1)} \\
\end{align}

```
````

````{admonition} Oefening 4
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{e^{x^2}}{ \sqrt{x^2+5} }
\end{align*}

```{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:
\begin{align*}
   f(x) =  \dfrac{e^{x^2}}{ \sqrt{x^2+5} }
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= e^{x^2} \\
  v &=  \sqrt{x^2+5} \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= e^{x^2} \cdot 2x \\
  \dfrac{du}{dx} &= 2xe^{x^2} \\
  \dfrac{dv}{dx} &=  \frac{1}{2}(x^2+5)^{-\frac{1}{2}} \cdot 2x \\
  \dfrac{dv}{dx} &=  \dfrac{x}{ \sqrt{ (x^2+5) } } \\
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ \sqrt{x^2+5} \cdot 2xe^{x^2} -  e^{x^2} \cdot  \dfrac{x}{ \sqrt{ (x^2+5) } }  }{ (\sqrt{x^2+5} )^2} \\
  &= \frac{ e^{x^2}( 2x\sqrt{x^2+5} - \dfrac{x}{ \sqrt{ (x^2+5)}} )}{ x^2+5 }  \\
  &= \frac{ e^{x^2}(  \dfrac{2x(x^2+5)-x}{ \sqrt{ (x^2+5)}} )}{ x^2+5 }  \\
  &= \frac{ e^{x^2}(  \dfrac{2x^3 +9x}{ \sqrt{ (x^2+5)}} )}{ x^2+5 }  \\
  &= \frac{ e^{x^2}(  2x^3 +9x )}{ (x^2+5)^{\frac{3}{2}} }  \\
\end{align}

```
````