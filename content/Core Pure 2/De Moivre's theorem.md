You can use [[Complex Numbers#Euler's Relation|Euler's relation]] to find powers of complex numbers that are given in [[Complex Numbers#Modulus Argument Form|Modulus argument form]]. 

> [!info]+ De Moivre's theorem proof 1
> 
> $$
> (r(\cos{\theta}+i\sin{\theta}))^2=(re^{i\theta})^2
> $$
>$$
>(re^{i\theta})\times(re^{i\theta})
>$$
> 
> $$
>r^2e^{i2\theta}
>$$ 
>$$
>r^2(\cos{2\theta}+i\sin{2\theta})
>$$
- This also applies for all other complex numbers in [[Complex Numbers#Modulus Argument Form|modulus argument form]]. 
This result is also known as **de Moivre's theorem**.

>[!info] De Moivre's theorem proof 2, using [[Complex Numbers#Euler's Relation|Euler's Relation]]
>
>
>$$
>(r(\cos{\theta}+i\sin{\theta}))^n=(re^{i\theta})^n
>$$
>
>$$
>r^{n}e^{in\theta}
>$$
>
>$$
>r^{n}(\cos{n\theta}+i\sin{n\theta})
>$$

- You can use [[De Moivre's theorem]] to dervice the trigonometric identities. 
- Applying the [[Binomial Expansion]] formula to $(\cos{\theta}+i\sin{\theta})^n$ lets you express $\cos(n\theta)$ in terms of $\cos{\theta}$, and lets you express $\sin{(n\theta)}$ in terms of $\sin{\theta}$.

Example 10
Use de Moivre's theorem to show that

$$
(cos{\theta}+i\sin{\theta})^6=\cos{6\theta}+i\sin{6\theta}
$$   
$$
=\cos^6{\theta}+C^{6}_{1}\cos5{\theta}
$$