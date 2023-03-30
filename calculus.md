# Calculus

## Differentiability

- LHD $\implies \lim\limits_{h \to o^-} \frac{f(c+h)-f(c)}{h}$
- RHD $\implies \lim\limits_{h \to o^+} \frac{f(c+h)-f(c)}{h}$
- Derivative $\implies \lim\limits_{h \to o} \frac{f(c+h)-f(c)}{h}$

## Formulae


- ### $\frac{d}{dx} ( k ) = 0$
- ### $\frac{d}{dx} ( x ) = 1$
- ### $\frac{d}{dx} ( u\pm v ) = \frac{d}{dx}(u) \pm \frac{d}{dx}(v)$
- ### $\frac{d}{dx}[f(x)]^n = n\cdot [f(x)]^{n-1}\cdot f'(x)$
- ### $\frac{d}{dx} [k\cdot f(x)] = k\cdot \frac{d}{dx} f(x)$
- ### $\frac{d}{dx} (u\cdot v) = u\cdot \frac{dv}{dx} + v\cdot \frac{du}{dx}$
- ### $\frac{d}{dx} (\frac{u}{v}) = \frac{v\cdot \frac{du}{dx} - u\cdot \frac{dv}{dx}}{v^2}$
- ### $\frac{d}{dx} e^{f(x)} = e^{f(x)}\cdot f'(x)$
- ### $\frac{d}{dx} a^{f(x)} = a^{f(x)}\cdot f'(x)\cdot \ln a$
- ### $\frac{d}{dx} \ln f(x) = \frac{1}{f(x)}\cdot f'(x)$
- ### $\frac{d}{dx} \sin f(x)  = \cos f(x) \cdot f'(x)$
- ### $\frac{d}{dx} \cos f(x)  = -\sin f(x) \cdot f'(x)$
- ### $\frac{d}{dx} \tan f(x)  = \sec^2 f(x) \cdot f'(x)$
- ### $\frac{d}{dx} \cot f(x)  = -\csc^2 f(x) \cdot f'(x)$
- ### $\frac{d}{dx} \sec f(x)  = \sec f(x) \cdot \tan f(x) \cdot f'(x)$
- ### $\frac{d}{dx} \csc f(x)  = -\csc f(x) \cdot \cot f(x) \cdot f'(x)$
- ### $\frac{d}{dx} \sin^{-1} x = \frac{1}{\sqrt{1-x^2}} \cdot f'(x)$

## Integration

- ### $\int f(x)^n dx = \frac{f(x)^{n+1}}{(n+1)f'(x)} + C$
- ### $\int dx = x + C$
- ### $\int k \cdot dx = kx + C$
- ### $\int\, cos f(x) dx = \frac{sin\, f(x)}{f'(x)} + C$ 
- ### $\int\, sin f(x) dx = -\frac{cos\, f(x)}{f'(x)} + C$
- ### $\int\, \sec^2 f(x) dx = \frac{tan\, f(x)}{f'(x)} + C$
- ### $\int\, \csc^2 f(x) dx = -\frac{cot\, f(x)}{f'(x)} + C$
- ### $\int\, sec f(x) \cdot tan f(x) dx = \frac{sec\, f(x)}{f'(x)} + C$
- ### $\int\, csc f(x) \cdot cot f(x) dx = -\frac{csc\, f(x)}{f'(x)} + C$
- ### $\int \frac{1}{\sqrt{1-x^2}} dx= sin^{-1} x + C$
- ### $-\int \frac{1}{\sqrt{1-x^2}} dx= cos^{-1} x + C$
- ### $\int \frac{1}{1+x^2} dx= tan^{-1} x + C$
- ### $-\int \frac{1}{1+x^2} dx= cot^{-1} x + C$
- ### $\int \frac{1}{x\sqrt{x^2-1}} dx = \sec^{-1} x + C$
- ### $-\int \frac{1}{x\sqrt{x^2-1}} dx = \csc^{-1} x + C$
- ### $\int e^{f(x)} dx = e^{f(x)} + C$
- ### $\int \frac{1}{f(x)} dx = \frac{\ln |f(x)|}{f'(x)} + C$
- ### $\int a^{f(x)} dx = \frac{a^{f(x)}}{f'(x)\cdot \log a} + C$
- ### $\int f(x)^n\cdot f'(x) dx = \frac{f(x)^{n+1}}{(n+1)f'(x)} + C$
- ### $\int \frac{f'(x)}{f(x)} dx = \ln |f(x)| + C$
- ### $\int linear \sqrt{linear} \implies \text{Put}\, \sqrt{linear} = t$
- ### $\int \tan f(x) dx = \frac{\log |\sec f(x)|}{f'(x)} + C = \frac{-\log |\csc f(x)|}{f'(x)} + C$
- ### $\int \cot f(x) dx = \frac{\log |\csc f(x)|}{f'(x)} + C$
- ### $\int \sec f(x) dx = \frac{\log |\sec f(x) + tan f(x)|}{f'(x)} + C$
- ### $\int \csc f(x) dx = \frac{\log |\csc f(x) + cot f(x)|}{f'(x)} + C$
- ### $\int \frac{1}{x^2-a^2} dx = \frac{1}{2a}\cdot \ln |\frac{x-a}{x+a}| + C$
- ### $\int \frac{1}{a^2+x^2} dx = \frac{1}{2a}\cdot \ln |\frac{a+x}{a-x}| + C$
- ### $\int \frac{1}{\sqrt{x^2-a^2}} dx = \log |x + \sqrt{x^2-a^2}| + C$
- ### $\int \frac{1}{\sqrt{a^2-x^2}} dx = \sin^{-1} \frac{x}{a} + C$
- ### $\int \frac{1}{\sqrt{x^2+a^2}} dx = \log |x + \sqrt{x^2+a^2}| + C$

...





