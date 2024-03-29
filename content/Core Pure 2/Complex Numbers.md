- The modulus-argument form of a complex number can be used to rewrite the complex number in the exponential form, $z=re^{i\theta}$. 

### Modulus Argument Form
Any complex number can be written in the terms of its modulus and argument.
- For a complex number $z$ with modulus $r$ and argument $\theta$. The modulus argument form is:

$$
z=r(\cos{\theta}+i\sin{\theta})
$$


### Euler's Relation

$$
e^{i\theta}=(\cos{\theta}+i\sin{\theta})
$$
- You can use Euler's relation and the modulus-argument form to write a complex number $z$ in an exponential form.
$$
z=re^{i\theta}
$$

- Where, $r=|z|$ and $\theta=\arg{z}$.   

>[!info]+ Example 1 
>Express $-2\sqrt{3}-2i$ in the form $\text{r}e^{i\theta}$.  
>
>- To find the value of $r$ we need to find the modulus and argument of the complex number.
>- To find the modulus we can use Pythagoras' theorem with both the real and imaginary parts of the number
>
>$$
>r=\sqrt{(-2\sqrt{3})^2+(-2)^2}=4
>$$
>- To find the argument we have two options, we can either put the number into the argument function on our calculators.
>- Or the more manual method, find the angle between the number from the origin, and the real axis in the direction $\rightarrow$. 
>- Sketching it out, we have a real part of length $2\sqrt{3}$, and imaginary part of length $2$. 
>- Here to find the angle between the complex number and the real axis, we have to first find the angle between the complex number and the imaginary axis, followed by adding $\frac{\pi}{2}$.
>- To find the angle between the complex number and imaginary axis we can do;
>
>$$
>\tan^{-1}({\frac{2\sqrt{3}}{2}})=\frac{1}{3}\pi
>$$
>- Then to find the angle between the complex number and the real axis, we add the angle between the imaginary axis and the real axis, which is $\frac{1}{2}\pi$.
>
>$$
>\frac{1}{3}\pi+\frac{1}{2}\pi=\frac{5}{6}\pi
>$$
>- However as the complex number is in the third quadrant, and under the real axis, the argument would have to be negative.
>- So $\theta = -\frac{5}{6}\pi$ and $r=4$.
In exponential form, the complex number $-2\sqrt{3}-2i$ would be:
>
>$$
>4e^{-i\frac{5}{6}\pi}
>$$

###### Euler's Identiy
- When subsituting $\theta=\pi$ and rearranging in [[Complex Numbers#Euler's Relation|Euler's relation]], we get Euler's Identity.
$$
e^{i\pi}+1=0
$$

#### Expansions of $\cos{\theta}$, $\sin{\theta}$ and $e^x$
- Both $\cos{\theta}$ and $\sin{\theta}$ can be written as an infinite series of powers of $\theta$.

$$
\cos{\theta}=1-\frac{\theta^2}{2!}+\frac{\theta^4}{4!}-\frac{\theta^6}{6!}...
$$

$$
\sin{\theta}=\frac{\theta}{1!}-\frac{\theta^3}{3!}+\frac{\theta^5}{5!} - \frac{\theta^7}{7!} ...
$$

- Both of the series for $\sin{\theta}$ and $\cos{\theta}$ are found from the [[Maclaurin series expansions]] of each function. 
- An $e^x$ can also be written in a similar infinite expansion.

>[!info]- Expansion of e^x
>
>$$
>e^{i\theta}=1+i\theta+\frac{(i\theta)^2}{2!}+\frac{(i\theta)^3}{3!}+\frac{(i\theta)^4}{4!}+\frac{(i\theta)^5}{5!}+\frac{(i\theta)^6}{6!}+\dots
>$$
>
>$$
>e^{i\theta}=1+i\theta-\frac{\theta^2}{2!}-\frac{\theta^3}{3!}i^+\frac{\theta^4}{4!}+\frac{\theta^5}{5!}i-\frac{\theta^6}{6!}+\dots
>$$
>
>$$
>e^{i\theta}=(1-\frac{\theta^2}{2!}+\frac{\theta^4}{4!}-\frac{\theta^6}{6!}\dots)+ i(\theta+-\frac{\theta^3}{3!}+\frac{\theta^5}{5!}\dots)
>$$

$$
e^{i\theta}=(1-\frac{\theta^2}{2!}+\frac{\theta^4}{4!}-\frac{\theta^6}{6!}\dots)+ i(\theta+-\frac{\theta^3}{3!}+\frac{\theta^5}{5!}\dots)
$$

### Multiplying and dividing complex numbers
For any two complex numbers $z_1$ and $z_2$ in either [[Complex Numbers#Modulus Argument Form|modulus argument form]].
- $|z_{1}z_{2}|=|z_1||z_2|$
- $\arg{(z_{1}z_{2})}=\arg{(z_1)}+\arg{(z_2)}$
- $|\frac{z_1}{z_2}|= \frac{|z_1|}{|z_2|}$
- $\arg{(\frac{z_1}{z_2})}=\arg{(z_1)}-arg{(z_2)}$


### Trigonometric Identities
[[De Moivre's theorem]] can be used to also derive the trigonometric identities, by using a [[Binomial Expansion]] with $(\cos{\theta}+i\sin{\theta})^n$, you can;
- Express $\cos{n\theta}$ in terms of powers of $\cos{\theta}$
- Express $\sin{n\theta}$ in terms of powers of $\sin{\theta}$

This also lets you find trigonometric identities for $\sin^n{\theta}$ and $\cos^n{\theta}$ in terms of $z$, where $z=\cos{\theta} + i\sin{\theta}$.

$$
z+\frac{1}{z}=2\cos\theta
$$

> [!info]- See how
>
>$$
>z+\frac{1}{z}=\cos{\theta}+i\sin{\theta}+\cos{\theta}-i\sin{\theta}=2\cos{\theta}
>$$

>[!info]- Formula for cos^n
>
>$$
>z^n+\frac{1}{z^n}=2\cos{n\theta}
>$$

$$
z-\frac{1}{z}=2i\sin\theta
$$

> [!info]- See how
>
>$$
>z-\frac{1}{z}=\cos{\theta}+i\sin{\theta}-\cos{\theta}+i\sin{\theta}=2i\sin{\theta}
>$$

>[!info]- Formula for sin^n
>
>$$
>z^n-\frac{1}{z^n}=2i\sin{n\theta}
>$$

### Sums of series
