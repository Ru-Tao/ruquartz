
- Hyperbolic functions are functions similar to the [[Trigonometric Functions]], but rather then being based on points on a unit circle like trigonometric functions are, hyperbolic functions are based on points on a hyperbola. 
- The hyperbola has the form $x^2-y^2=1$, similar to the unit circle that has the equation $x^2+y^2=1$. 
- The Cartesian coordinates for a point on this hyperbola are given by the functions $\cosh{x}$ and $\sinh{x}$.

## Key Points
- All hyperbolic functions can be defined in terms $e$.

##### Hyperbolic function definitions

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

##### The graphs of the hyperbolic functions
$$
\sinh{x}
$$
![[sinh-graph.png]]

>[!info]- Easy way to remember the sinhx graph.
>
>- Defining $\sinh{x}$, we know in exponentials it can be given in the form $\frac{e^{x}-e^{-x}}{2}$
>- To sketch the graph, you can actually consider $y=sinh{x}$ to be the "**average**" of the $y=e^x$ and $y=-e^-x$ graphs.
>
>![[sinh-e^x--e^x.png]]

$$
\cosh{x}
$$
![[coshx-graph.png]]

>[!info]- Easy way to remember the coshx graph.
>
>- Defining $\sinh{x}$, we know in exponentials it can be given in the form $\frac{e^{x}+e^{-x}}{2}$
>- To sketch the graph, you can actually consider $y=cosh{x}$ to be the "**average**" of the $y=e^x$ and $y=e^-x$ graphs.
>
>![[cosh-e^x-e^-x.png]]

##### Reciprocal Hyperbolic Functions and definitions

Alongside these $\sinh$, $\cosh$ and $\tanh$ there also exists reciprocal hyperbolic functions, similar to the reciprocal trigonometric functions.

$$
\text{cosech}{x}=\frac{1}{\sinh{x}}=\frac{1}{e^{x}-e^{-x}}
$$

$$
\text{sech}{x}=\frac{1}{\cosh{x}}=\frac{1}{e^{x}+e^{-x}}
$$

$$
\coth{x}=\frac{1}{\tanh{x}}=\frac{e^{2x}-1}{e^{2x}+1}
$$

>[!question]+ Example 1
>
>Find, to 2 decimal places, the values of:
>a) $\sinh{3}$
>b) $\cosh{1}$
>c) $\tanh{0.8}$
><small>Taken from Edexcel A Level Further Mathematics - Core Pure Mathematics Book 2 Chapter 6 Example 1</small>
>
>>[!todo]- Answer
>>
>>$$
>>a) \sinh{3}=\frac{e^{3}-e^{-3}}{2}=10.02
>>$$
>>$$
>>b) \cosh{3}=\frac{e^{1}+e^{-1}}{2}=1.54 
>>$$
>>$$
>>c) \tanh{3}=\frac{e^{1.6}+1}{e^{1.6}-1}=0.66 
>>$$

>[!question]+ Example 2
>
>Use the [[Hyperbolic functions#Hyperbolic function definitions|definition of sinh(x)]] to find, to 2 decimal places, the value of $x$ for which $\sinh{x}=5$
><small>Taken from Edexcel A Level Further Mathematics - Core Pure Mathematics Book 2 Chapter 6 Example 3</small>
>
>>[!todo]- Answer
>>
>>- We can start by defining $\sinh{x}$ and equating it to $5$. 
>>$$
>>\sinh{x}=\frac{e^{x}-e^{-x}}{2}=5
>>$$
>>
>>- Multiply the $5$ on on the right hand side by 2. 
>>
>>$$
>>e^{x}-e^{-x}=10
>>$$
>>
>>- At this point the equation actually becomes a hidden quadratic, where instead of $x$, we have $e^x$. 
>>- To show this, we can multiply everything by $e^x$.
>>
>>$$
>>e^{2x}-1=10e^x
>>$$
>>- Moving everything to one side makes it even clearer. 
>>
>>$$
>>e^{2x}-10e^{x}-1=0
>>$$
>>- Now, all we have to do is solve for $e^x$. 
>>
>>$$
>>e^x=5\pm \sqrt{26}
>>$$
>>So this means, 
>>
>>$$
>>x=\text{ln}(5+\sqrt{26})
>>$$
>>- We disqualify $e^x=5-\sqrt{26}$ as $5-\sqrt{26}$ is a negative number, and as a result wouldn't be able to be logged to find x. 
