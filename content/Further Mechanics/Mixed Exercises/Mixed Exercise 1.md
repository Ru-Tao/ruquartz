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

