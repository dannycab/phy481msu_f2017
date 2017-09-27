---
layout: slide
theme: white
transition: slide
---

<section data-markdown>

We derived the electric potential outside ($r>R$) the charged shell to be

$$V(r) = \dfrac{1}{4\pi\varepsilon_0}\dfrac{q}{r}$$

What is it for $r<R$?

1. Zero
2. Constant
3. It changes but I don't know how yet
4. Something else

Note:
* Correct Answer: B

</section>

<section data-markdown>
### Exam 1 Information

* Exam 1 on Wednesday, October 4th (A149 PSS)
  - Across from FRIB (Wilson side)
* 7pm-9pm
  - Arrive on time!
* I will provide a formula sheet (posted on Piazza already)
* You can bring one-side of a sheet of paper with your own notes.
* 4 questions - True/False, Essay, Graphing, Calculations

</section>

<section data-markdown>

### What's on Exam 1?

* Identify whether conceptual statements about $\mathbf{E}$, $V$, $\rho$, and/or numerical integration are true or false.
* Sketch and discuss delta functions in relation to charge density, $\rho$
* Calculate the electric field, $\mathbf{E}$, inside and outside a continuous distribution of charge and sketch the results
* Calculate the electric potential, $V$, for a specific charge distribution and discuss what happens in limiting cases

</section>

<section data-markdown>

<img src="./images/graph_shell.png" align="center" style="width: 400px";/>

Could this be a plot of $\left|\mathbf{E}(r)\right|$? Or $V(r)$? (for SOME physical situation?)

1. Could be $E(r)$, or $V(r)$
2. Could be $E(r)$, but can't be $V(r)$
3. Can't be $E(r)$, could be $V(r)$
4. Can't be either
5. ???

Note:
* Correct Answer: B

</section>

<section data-markdown>

We usually choose $V(r\rightarrow\infty) \equiv 0$ when calculating the potential of a point charge to be $V(r) = +kq/r$. How does the potential $V(r)$ change if we choose our reference point to be $V(R) = 0$ where $R$ is close to $+q$.

1. $V(r)$ higher than it was before
2. $V(r)$ is lower than it was before
4. $V(r)$ doesn’t change ($V$ is independent of  choice of reference)

Note:
* CORRECT ANSWER: B
* Show redefinition.


</section>

<section data-markdown>

### Electrostatic Potential Energy

<img src="./images/cathode_ray_tube.png" align="center" style="width: 600px";/>

</section>

<section data-markdown>

<img src="./images/three_charges.png" align="right" style="width: 300px";/>

Three identical charges $+q$ sit on an equilateral triangle. What would be the final $KE$ of the top charge if you released it (keeping the other two fixed)?

1. $\frac{1}{4\pi\varepsilon_0}\frac{q^2}{a}$
2. $\frac{1}{4\pi\varepsilon_0}\frac{2q^2}{3a}$
3. $\frac{1}{4\pi\varepsilon_0}\frac{2q^2}{a}$
4. $\frac{1}{4\pi\varepsilon_0}\frac{3q^2}{a}$
5. Other

Note:
CORRECT ANSWER: C

</section>

<section data-markdown>

<img src="./images/three_charges.png" align="right" style="width: 300px";/>

Three identical charges $+q$ sit on an equilateral triangle. What would be the final $KE$ of the top charge if you released *all three*?

1. $\frac{1}{4\pi\varepsilon_0}\frac{q^2}{a}$
2. $\frac{1}{4\pi\varepsilon_0}\frac{2q^2}{3a}$
3. $\frac{1}{4\pi\varepsilon_0}\frac{2q^2}{a}$
4. $\frac{1}{4\pi\varepsilon_0}\frac{3q^2}{a}$
5. Other

Note:
CORRECT ANSWER: A

</section>

<section data-markdown>

Does system energy "superpose"?

That is, if you have one system of charges with total stored energy $W_1$, and a second charge distribution with $W_2$...if you superpose these charge distributions, is the total energy of the new system simply $W_1 + W_2$?

1. Yes
2. No

Note:
* CORRECT ANSWER: B
* Draw 4 charges and show that it is not the sum of the 2 charges and the other 2.

</section>

<section data-markdown>

<img src="./images/pt_charges_energy.png" align="center" style="width: 300px";/>


Two charges, $+q$ and $-q$, are a distance $r$ apart.  As the charges are slowly moved together, the total field energy

$$\dfrac{\varepsilon_0}{2}\int E^2 d\tau$$

1. increases
2. decreases
3. remains constant

Note:
* CORRECT ANSWER: B
* Consider when they overlap, field goes to zero, must be E gets smaller as they get closer. same volume
</section>

<section data-markdown>

<img src="./images/capacitor_pull_apart.png" align="center" style="width: 500px";/>


A parallel-plate capacitor has $+Q$ on one plate, $-Q$ on the other.  The plates are isolated so the charge $Q$ cannot change.  As the plates are pulled apart, the total electrostatic energy stored in the capacitor:

1. increases
2. decreases
3. remains constant.

Note:
* CORRECT ANSWER: A
* Same E; constant; larger volume where it is non-zero
</section>
