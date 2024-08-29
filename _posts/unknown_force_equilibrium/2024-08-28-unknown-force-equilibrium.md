---
layout: post
title:  Solving for Unknown Force Equilibrium (E&M)
date:   2024-08-26 14:02:00 +0000
categories: jekyll update
usemathjax: true
---

Wow! Yet another Electricity and Magnetism post. While reviewing basic electric charges and forces, I found the problem below:
> Two positive point charges \\(q\\) and \\(4q\\) are at \\(x=0\\) and \\(x=L\\) respectively, and free to move. A third charge is placed so that the entire three-charge system is in static equilibrium. What are the magnitude, sign, and \\(x\\)-coordinate of the third charge?

The following is my approach to solving this problem:

First, we must narrow down the possible positions of the third point charge. We notice that any position not collinear with the other two charges with create non-zero \\(y\\)-components of the force vectors between each of the charges and thus we can deduce that the third charge must be collinear with the original two charges.

Next, we can notice that any position that is not in between each of the two original charges will cause non-zero \\(x\\)-components of the force vectors. We can also deduce that the third charge must be negative in order to create static equilibrium.

Knowing the above, we can set up a system of equations:

$$
\frac{kqQ}{x^2}=-\frac{k(4q)q}{L^2}, \; \frac{k(4q)Q}{x^2}=-\frac{k(4q)q}{L^2}
$$

Where \\(x\\) is the distance on the \\(x\\)-axis that the third charge is and \\(Q\\) is the magnitude of the third charge.

Combining both the equations due to their equal right sides, we get

$$
\frac{kqQ}{x^2}=\frac{k(4q)Q}{x^2}
$$

Which can be simplified to 

$$
4x^2=(L-x)^2 \; \Rightarrow \; 2x=L-x \; \Rightarrow \; 3x=L \; \Rightarrow \; x=\frac{L}{3}
$$

Substituting \\(x\\) into the first equation in, we get

$$
\frac{kqQ}{\frac{L^2}{9}}=\frac{4kq^2}{L^2} \; \Rightarrow \; Q=-\frac{4}{9}q
$$