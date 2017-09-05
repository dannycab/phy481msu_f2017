---
layout: homework
use_math: true
---

# Homework 3 (Due September 20th)

#### 5. Ring of charge - Motion of a test charge

While we spend a large amount of time working with source charges and the electric fields that they produce, we are ultimately concerned about their effect on the motion of other charges (so-called "test charges"). In this problem, you will work with the electric field due to a ring of charge to develop an approximate solution for the motion of a test charge by "linearizing" the differential equation that describes the motion. In working this problem, you will have to dust off some of your classical mechanics knowledge regarding differential equations.

Consider a thin ring (positive charge, $Q$; radius, $a$) that has its central axis directed along the $x$-direction as shown.

![Ring of charge](./images/hw2/ring_w_charge.png "Ring of Charge")

A charged ring with these parameters will produce an electric field along its central axis given by,

$$E_x = \dfrac{1}{4\pi\varepsilon_0}\dfrac{Qx}{\left(x^2+a^2\right)^{3/2}}$$

1. Write down the differential equation that describes the motion of a particle with negative charge $-q$ and mass $m$ that is carefully positioned on the $x$-axis. *Note: this particle has a charge that is opposite the sign of the ring, so $q$ is the magnitude of the charge of this particle.*
2. What kind of motion do you expect to see for this charge? Why? Does the differential equation describe that kind of motion? *Hint: Consider if this differential equation is analytically tractable (i.e., can it be solved in closed form).*
3. Consider the situation where the particle is very close to a large ring (i.e., where $x/a\;<<\;1$). Determine the approximate form of the differential equation for this case -- keep only terms that depend linearly on $x$. This is called "linearizing" the differential equation and makes the solution analytically tractable.
4. Solve the differential equation for the case where the particle starts from rest at a distance of $x_0$ from the ring. Sketch the resulting motion of the test charge as a function of time. Does your graph agree with your intuition about the motion?
5. What would happen to the test charge if it was not placed precisely on the central axis? Why?
6. We have created a Jupyter notebook that models the motion of the test charge using both the exact and the approximate differential equation. You can [download it here](../jupyter/HW2-MotionOfTestCharge.ipynb) (or [view it here](https://github.com/dannycab/phy481msu/blob/gh-pages/jupyter/HW2-MotionOfTestCharge.ipynb)). By working through this notebook, we expect you to be able to explain the output of each model and its assumptions. We also ask that you determine under what conditions the approximate model is a good one and explain how you know.


#### 6. Finding the electric field of spherical shell using direct integration

In this class, you will learn a mathematical technique (Gauss' Law) that makes solving for the electric field relatively simple in comparison to direct integration for certain kinds of problems. In this problem, you will solve for the electric field that can be determined using Gauss' Law, but you will use direct integration instead. This problem involves relatively sophisticated integral, which you are free to look up, have some software solve, or (for the gluttons for pain) solve yourself. The message here is: when you run across a difficult piece of math, it's ok to use your resources; just cite your sources!

1. Find the electric field a distance $z$ above the center of a spherical shell  of radius $R$, which carries a uniform surface charge density $\sigma$. Do this by explicit integration (i.e., starting from Griffith's equation 2.7), please. Just treat the case of $z > R$ (*outside* the sphere). Express your answer in terms of the total charge $q$ on the sphere. *Also, be careful, when you get a square root, to take the positive root:* $\sqrt{R^2 + z^2 - 2Rz}=(R-z)$ if $R>z$, but it's $(z-R)$ if $R<z$.
2. Check your answer using a units check and your knowledge from PHY 184. Briefly discuss what the answer should be outside the sphere. What should the answer be inside the sphere and why? *You don't have to solve that problem explicitly.*

*Historical note: Newton solved part 1 using geometry (no calculus!!) This geometric proof is tricky and still excites debate: see R. Weinstock Am. J. Phys., 52, (1984), p. 883; H. Erlichson, Am. J. Phys. 58, (1990) p. 882. Newton thought calculus should be kept secret, and held up publication of Principia until he could work out these non-calculus proofs. He published calculus much later, about the same time as Leibniz published his calculus.*
