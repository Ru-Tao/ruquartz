Mixed exercise 1 taken from Edexcel Further Mechanics 1.

> [!question]+ Question 2
>A pile driver of mass 1000kg drives a pile of mass 200kg vertically into the ground. The driver falls freely a vertical distance of 10m before hitting the pile. Immediately after the driver impacts with the pile it can be assumed that they both move with the same velocity. By modelling the pile and the driver as particles, find:
>
>a) The speed of the driver immediately before it hits the pile
>>[!todo]- Answer
>>
>>- For part **a**, [[Equations of Motion|suvat]] is actually to be used, as we are given the distance, and we're looking for the final speed of the driver before it hits the pile, $v$. 
>>- The starting speed, $u$, can be assumed to be 0 as it's falling from rest, 
>>- The acceleration, $a$, being $g$ or $9.8$ as its falling.
>>
>>$$
>>s=10\\ u=0\\ v=?\\ a=9.8\\ t=N/A
>>$$
>>
>>Knowing these three values, we can use the suvat equation $v^2=u^2+2as$ and find the value of $v$.
>>
>>$$
>>v^2=0^2+2(9.8)(10)
>>$$
>>
>>$$
>>v^2=196\\ v=14
>>$$
>
>
>b) The common speed of the pile and the driver immediately after the impact. 
>>[!todo]- Answer
>>
>>- To find the common speed, we can use [[Momentum#Conservation of Momentum|conservation of momentum]]. 
>>- For the driver we have its mass, $m_1$, as 1000.
>>- Its speed, $u_1$, being 14m/s, as found in part **a**. 
>>- For the pile we also have its mass, $m_2$,
>>- and its speed, $u_2$, of $0$. 
>>- As for $v_1$ and $v_2$ as both the pile and the driver fall together with the same velocity, I'll just label it $v$ (separate from the $v$ in part **a**).
>>
>>This gives us the equation,
>>
>>$$
>>14(1000)=1000v+200v
>>$$
>>
>>$$
>>14000=1200v
>>$$
>>
>>$$
>>\frac{14000}{1200}=v
>>$$
>>
>>$$
>>\frac{35}{3}=v
>>$$
>>
>>So the final velocity before it hits the pile would be $\frac{35}{3}m/s.$
>
>The ground provides a constant resistance of 120000N to the motion of the pile driver.
>c) Find the distance that the pile is driven into the ground before coming to a rest.
>> [!todo]- Answer
>>
>>- Here we actually have to use both the aforementioned [[Equations of Motion|suvat]] and the formula for [[Force|force]]. 
>>- Using the formula $F=ma$, we can find the force that pile and the driver combined exerts, 
>>
>>$$
>>F=(1200)(9.8)
>>$$
>>
>>$$
>>F=11760
>>$$
>>
>> - and taking away this value from the force exerted by the ground we can then find the overall force of the equation.
>>$11760-120000=-108240$
>>- With this value we can find the overall acceleration, once again using $F=ma$.
>>
>>$$
>>-108240=1200(a)
>>$$
>>
>>$$
>>a=-\frac{108240}{1200}
>>$$
>>
>>$$
>>a=-90.2
>>$$
>>
>>- Here, we can use the suvat equation $v^2=u^2+2as$ to find the distance, $s$. 
>>
>>$$
>>s=?\\
>>u=\frac{35}{3}\\
>>v=0 \text{(As it comes to a stop.)}\\
>>a=-90.2\\
>>t=N/A
>>$$
>>- Plugging these values into the equation we get, 
>>
>>$$
>>0=(\frac{35}{3})^2+2(-90.2)s
>>$$
>>
>>$$
>>180.4s=(\frac{1225}{9})
>>$$
>>
>>- Dividing $\frac{1225}{9}$ by 180.4, we can get the value of $s$
>>$s=0.754\dots$
>>So the overall distance travelled before coming to a stop is 0.754m. (3 significant figures.)
>
>d) Comment on this model in relation to the motion of the pile and the driver immediately after impact.
>> [!todo]- Answer
>>
>>The model assumes that the pile and the driver comes to an absolute stop, and doesn't "bounce".
>>

> [!question]+ Question 3
>A car of mass 800kg is travelling along a straight horizontal road. A constant $FN$ reduces the speed of the car from 18m/s to 12m/s in 2.4s.
><small>Assume the car to be moving in the direction $\rightarrow$ </small>
>a) Calculate the value of F
>
>> [!todo]- Answer
>>
>>- Here to find the force impacting the car, we can use the [[Force|force]] formula, $F=ma$.
>>- However as we are missing the acceleration of the car as it slows down, we can't use the formula straight away.
>>- So to find the acceleration, we can use the [[Equations of Motion#Equations|suvat]] equation, $v=u+at$.
>>- As the force is acting against the car that is moving in the direction $\rightarrow$, the F would be acting in the opposite direction $\leftarrow$, meaning the force is -F.
>>
>>$$
>>s = N/A \\
>>u=18 \\
>>v=12 \\
>>a=? \\
>>t=2.4 \\
>>$$
>>
>>$$
>>12=18+2.4a
>>$$
>>
>>Rearranging the equation for $a$ we get, 
>>$a=-2.5$
>>- Now as we have $a$ we can find the overall force $F$, 
>>$-F=(800)(-2.5)$
>>$F=2000N$
>
>b) Find the distance moved by the car in these 2.4s.
>
>> [!todo]- Answer
>>
>>- Here we can use suvat again. I decided to go with the equation $s=(\frac{u+v}{2})t$.
>>Plugging the values we had previously we get the equation
>>
>>$$
>>s=(\frac{18+12}{2})2.4
>>$$
>>Which solving gives the answer of 
>>$s=36\text{m}$
>>So the car moved $36\text{m}$ within the $2.4$ seconds.

> [!question]+ Question 4
>Two particles $A$ and $B$, of masses 0.2kg and 0.3kg respectively are free to move in a smooth horizontal groove. Initially $B$ is at rest and $A$ is moving towards $B$ with a speed of $4m/s$. After the impact the speed of $B$ is $1.5m/s$.
>a) Find the speed of $A$ after the impact
>>[!todo]- Answer
>>
>>- As we are given the masses of the two particles alongside the speed before and the speed after for $B$, we can use the [[Momentum#Conservation of Momentum|conservation of momentum]] formula to find the speed of $A$.
>>- Assuming $A$ is moving in the direction $\rightarrow$.
>>
>>$$
>>m_{1}u_{1} + m_{2}u_{2} = m_{1}v_{1} + m_{2}v_{2}
>>$$
>>
>>$$
>>m_1=0.2kg \quad m_2=0.3kg
>>$$
>>
>>$$
>>u_1=4m/s \quad u_2=0m/s
>>$$
>>
>>$$
>>v_1=?m/s \quad v_2=1.5m/s
>>$$
>>
>>$$
>>0.2(4) = 0.2v_{1} + 0.3(1.5)
>>$$
>>Rearranging the equation we can find $v_1$
>>
>>$$
>>v_1=1.75m/s
>>$$
>>
>>b) Find the magnitude of the impulse of B on A during the impact.
>>- Here we just use the [[Impulse#Impulse momentum principle.|impulse formula]]. 
>>$$
>>I=mv-mu
>>$$
>>
>>$$
>>I=(0.2)(1.75)-(0.2)(4) \\
>>I= -0.45Ns
>>$$
>>The overall magnitude of the impulse would be $0.45Ns$

>[!question]+ Question 5
>
> A railway truck, $P$, of mass $2000kg$ is moving along a straight horizontal track with speed $10m/s$. The truck $P$ collides with truck $Q$ of a mass $3000kg$, which is at rest on the same track. Immediately after the collision, $Q$ moves with speed $5m/s$.
a) Calculate the speed of P immediately after the collision.
>> [!todo]- Answer
>> 
>> - Here was can use the [[Momentum#Conservation of Momentum|conservation of momentum formula]] to find the speed of P after collision, $v_2$.
>> 
>> $$
>> m_{1}u_{1} + m_{2}u_{2} = m_{1}v_{1} + m_{2}v_{2}
>> $$
>> - $m_1=2000kg$ $m_2=3000kg$.
>> - $u_1=10m/s$ $u_2=0$
>> - $v_1=? v_2=5m/s$
>> Plugging in these values into the formula we get
>> 
>> $$
>> (2000)(10)=2000v_2+3000(5)
>> $$
>> 
>> Rearranging the formula for $v_2$ we get
>> 
>> $$
>> v_2=2.5m/s
>>$$
> 
>b) Calculate the magnitude of the impulse exerted by $P$ on $Q$ during the collision.
>>[!todo]- Answer
>>
>> - Here we use the [[Impulse#Impulse momentum principle.|impulse formula]] and plug in our previous values for $P$
>> $$
>> I=mv-mu
>> $$
>> $$
>> I=(2000)(2.5)-(2000)(10)\\
>> I=-15000Ns
>> $$
>> So the magnitude of the impulse of $P$ on $Q$ is $15000Ns$

>[!question]+ Question 6
>
>A particle, $P$, of mass $1.5kg$ is moving along a straight horizontal line with speed $3m/s$. Another particle $Q$ of mass $2.5kg$ is moving in the opposite direction, along the same straight line with speed $4m/s$ The particles collide. Immediately after the collision the direction of motion of $P$ is reversed and its speed is $2.5m/s$.
>a) Calculate the speed of Q immediately after the impact.
>>[!todo]- Answer
>>
>>- Here to find the speed, or velocity, after the impact we can use the conservation of momentum.
>>- We can assume particle $P$ to be moving in the direction $\rightarrow$.
>>- Since particle $Q$ is moving in the opposite direction, $\leftarrow$ , the value of $u_2$ would be negative.
>> For particle $P$: $m_1=1.5$ $u_1=3$ $v_1=-2.5$ 
>> For particle $Q$: $m_2=2.5$ $u_2=-4$ $v_2=?$
>> - We can plug these values into the equation:
>>
>>$$
>>m_{1}u_{1} + m_{2}u_{2} = m_{1}v_{1} + m_{2}v_{2} 
>>$$
>>
>>$$ 
>>(1.5)(3) + (2.5)(-4) = (-2.5)(1.5) + (2.5)v_{2} 
>>$$
>>
>>Rearranging the equation we are given $v_2=0.8m/s$.
>
>b) State whether or not the direction of motion of $Q$ is changed by the collision.
>>[!todo]- Answer
>>
>>- The Direction of motion **has** changed.
>>- This can be spotted as there was a change in sign between $u_2$ and $v_2$, meaning that the particle changed direction. 
>
>c) Calculate the magnitude of the impulse exerted by $Q$ on $P$.
>> [!todo]- Answer
>> 
>>- Here like all previous impulse questions we can use the [[Impulse#Impulse momentum principle.|Impulse momentum formula]].
>>
>>$$ 
>>I=mv-mu 
>>$$
>>
>>$$ 
>>I=(2.5)(0.8)-(2.5)(-4) 
>>$$
>>
>>$$ 
>>I=12Ns 
>>$$
>>So the magnitude of impulse exerted by $Q$ on $P$ is $12Ns$
>>

>[!question]+ Question 7
> A particle $A$ of mass $m$ is moving with speed $2u$ in a straight line on a smooth horizontal table. It collides with another particle $B$ of mass $km$ which is moving in the same straight line on the table with speed $u$ in the opposite direction to $A$. In the collision, the particles form a single particle which moves with speed $\frac{2}{3}u$ in the original direction of $A$'s motion. Find the value of $k$.
>
>>[!todo]- Answer
>>
>> 
>> - Assuming particle A is moving in the positive direction $\rightarrow$, particle $B$ would be moving in the direction $\leftarrow$, as a result the value of $B$'s speed would be $-u$.
>>- Here we can use the [[Momentum#Conservation of Momentum|conservation of momentum]] formula.
>>
>>$$
>>m_{1}u_{1} + m_{2}u_{2} = m_{1}v_{1} + m_{2}v_{2}
>>$$
>>- For particle $A$ we have $m_1=m$ and $u_1=2u$
>>- For particle $B$ we have $m_2 = km$ and $u_2=-u$
>>- For the right hand side of the formula, as A and B join together, and both move at the same speed of $\frac{2}{3}u$, we would have $(m+km)\frac{2}{3}u$
>>Plugging in all of these values into the formula we get.
>>
>>$$
>>2mu - kmu = \frac{2}{3}mu+\frac{2}{3}kmu
>>$$
>>- Dividing both sides by $mu$ we get 
>>
>>$$
>>2- k = \frac{2}{3}+\frac{2}{3}k
>>$$
>>
>>$$
>>\frac{4}{3}=\frac{5}{3}k
>>$$
>>Solving the equation for k we get
>>
>>$$
>>k=\frac{4}{5}
>>$$

> [!question]+ Question 8
> A metal pin of mass $2kg$ is driven vertically into the ground by a blow from a sledgehammer of mass $10kg$. The hammer falls vertically on to the pin, its speed just before impact being $9m/s$. In a model of the situation it is assumed that, after the impact, the pin and the hammer stay in contact and move together before coming to rest.
> a) Find the speed of the pin immediately after impact.
> 
>>[!todo]- Answer
>> 
>> - Here conservation of momentum can be used.
>> - For the hammer, $m_1=10$ and $u_1=9$ 
>> - For the pin, $m_2=2$ and $u_2=0$ 
>> - For the left hand side of the equation, as both the pin and hammer move together, the mass would be $10+2$, and the speed of the combined object can be called $v$. 
>> 
>>$$
>>m_{1}u_{1} + m_{2}u_{2} = m_{1}v_{1} + m_{2}v_{2}
>>$$
>> 
>> $$
>>(10)(9) = (12)(v)
>>$$
>>Solving for $v$ we can find, 
>> 
>> $$
>> v=\frac{15}{2}
>> $$
>> So the speed of the pin immediately after impact would be $7.5m/s$.
>
>The pin moves $3cm$ into the ground before coming to rest. Assuming in this model the ground exerts a constant restive force of $R$ newtons as the pin is driven down.
>
> b) Find the value of R
>
>> [!todo]- Answer
>> 
>> - Here to find the value of the [[Force|force]], $R$, we can use the force formula, $F=ma$.
>> - The force were looking for would be the $12(9.8)-R$ as $ma$ would be equal to the overall force of the equation.
>> - However we need to firstly find the acceleration of the pin as it slows down. 
>> - We can do this by forming a [[Equations of Motion#Equations|suvat]] equation using the values we do have.
>> 
>> $$
>> s=0.03m \\
>> u=7.5m/s \\
>> v=0m/s \\
>> a=? \\
>> t=N/A
>> $$
>> $$
>> v^2=u^2+2as
>> $$
>> $$
>> 0=\frac{225}{4}+\frac{3}{50}a
>> $$
>> $$
>>a=-\frac{1875}{2}
>>$$
>> So acceleration (or rather deceleration) in this case is $-937.5m/s^2$.
>> - Now we have the mass and acceleration, we can plug in the values into the Force formula to find the overall force acting on the hammer and pin.
>> 
>> $$
>>12(9.8)-R=(12)(-937.5)
>>$$
>> Rearranging to find R
>> $12(9.8)-(12)(-937.5)=R$
>> $117.6+11250=R$
>> 
>> $$
>> R = 11367.6
>> $$
>> So the resisting force from the ground would be $11367.6N$. 
>
>c)State in one way which the model might be refined to be more realistic.
>
>>[!todo]- Answer
>>
>>The resistance R could be modelled with varying speed.

>[!question]+ Question 9
>
A cricket ball of mass $0.5kg$ is struck by a bat. Immediately before being struck the velocity of the bat is $(-25i)\text{m/s}$. Immediately after being struck the velocity of the ball is $(23i+20j)\text{m/s}$.
>
Find the magnitude of impulse exerted on the ball by the bat and the angle between the impulse and the direction i. 
>
>>[!todo]- Answer
>>
>>- In this question velocity is given to us in [[Vectors#2D Vectors|vector notation]].
>>- Despite this the formula for [[Impulse#Impulse momentum principle.|impulse]] remains the same.
>>
>>$$
>>I=mv-mu
>>$$
>>
>>$$
>>I=0.5\begin{pmatrix}23\\ 20\end{pmatrix}-(0.5)\begin{pmatrix}-25\\ 0\end{pmatrix}
>>$$
>>
>>$$
>>I=0.5\begin{pmatrix}48\\ 20\end{pmatrix}
>>$$
>>
>>$$
>>I=\begin{pmatrix}24\\ 10\end{pmatrix}
>>$$
>>
>>- Here we can use the formula for [[Vectors#The magnitude of a vector|the magnitude of the vector]].
>>
>>$$
>>|I|=\sqrt{24^2+10^2}
>>$$
>>
>>$$
>>|I|=26
>>$$
>>- To find the angle between the impulse and direction **i**, is just to find the angle between the impulse vector and the x axis.
>>- We can create a triangle with a base of 10, 
>>
>>```tikz
>>\begin{document}
>>  \begin{tikzpicture}
>>	\draw (0,0) node[anchor=north]{$A$}
>>	  -- (12,0) node[anchor=north]{$C$}
>>	  -- (12,5) node[anchor=south]{$B$}
>>	  -- cycle;
>>	\node[label={26} ] at (6,2.5) {};
>>	\node[label={24} ] at (6,-1) {};
>>	\node[label={10} ] at (12.5, 2) {};
>>
>>  \end{tikzpicture}
>>\end{document}
>>```
>>- Here we have to find the angle $\angle BAC$, as the line $AB$ is the vector $I$, and $AC$ is the vector $i$, also known as the x axis.
>>- Here we can use any trig function to find the angle as we have all 3 sides
>>- I will opt to use $\cos$ since its my favourite. 
>> 
>>$$
>> \cos^{-1}(\frac{24}{26})=22.6199
>>$$
>>- So the angle between the vector $I$ and the line $i$ is $22.6199\textdegree.$    



