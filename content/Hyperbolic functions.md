- Hyperbolic functions are functions similar to the [[trigonometric functions]], but rather then being based on points on a unit circle like trigonometric functions are, hyperbolic functions are based on points on a hyperbola. 
- The hyperbola has the form $x^2-y^2=1$, similar to the unit circle that has the equation $x^2+y^2=1$. 
- The Cartesian coordinates for a point on this hyperbola are given by the functions $\cosh{x}$ and $\sinh{x}$.

## Key Points
- All hyperbolic functions can be defined in terms $e$.

$$
\sinh{x}=\frac{e^{x}-e^{-x}}{2}
$$
$$
\cosh{x}=\frac{e^{x}+e^{-x}}{2}
$$

$$
\tanh{x} \text{ can be defined as } \frac{\sinh{x}}{\cosh{x}}
$$

$$
\tanh{x} = \frac{e^{2x}+1}{e^{2x}-1}.
$$
> [!info]- How to get from sinhx/coshx to the exponential form of tanhx
>
> - To start we can establish the values of $\sinh{x}$ and $\cosh{x}$.
>
>$$
>\sinh{x}=\frac{e^{x}-e^{-x}}{2}
>$$
>
>$$
>\cosh{x}=\frac{e^{x}+e^{-x}}{2}
>$$
>- As, $\tanh{x}=\frac{\sinh{x}}{\cosh{x}}$, we can put $\sinh{x}$ and $\cosh{x}$ in their exponential forms to begin to find the exponential form of $\tanh{x}$.
>
>$$
>\frac{\sinh{x}}{\cosh{x}}=\frac{e^{x}-e^{-x}}{2}\times \frac{2}{e^{x}+e^{-x}}
>$$
>
>$$
>\frac{\sinh{x}}{\cosh{x}}=\frac{e^{x}-e^{-x}}{e^{x}+e^{-x}}
>$$
>- Now multiplying the entire fraction by $\frac{e^x}{e^x}$, we can find the final form. 
>
>$$
>\frac{e^{x}-e^{-x}}{e^{x}+e^{-x}}\times\frac{e^x}{e^x}=\frac{e^{2x}+1}{e^{2x}-1}
>$$
>
>$$
>\tanh{x}=\frac{e^{2x}+1}{e^{2x}-1}
>$$

Alongside these $\sinh$, $\cosh$ and $\tanh$ there also exists reciprocal hyperbolic functions, similar to the reciprocal trigonometric functions.

$$
\DeclareMathOperator{\sech}{sech}
\DeclareMathOperator{\cosech}{cosech}
\DeclareMathOperator{\coth}{coth}

\cosech{x}=\frac{1}{\sinh{x}}=\frac{1}{e^{x}-e^{-x}}
$$

$$
\sech{x}=\frac{1}{\cosh{x}}=\frac{1}{e^{x}+e^{-x}}
$$

$$
\coth{x}=\frac{1}{\tanh{x}}=\frac{e^{2x}-1}{e^{2x}+1}
$$