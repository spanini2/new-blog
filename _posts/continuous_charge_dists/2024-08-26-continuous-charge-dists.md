---
layout: post
title:  Continuous Charge Distributions
date:   2024-08-26 14:02:00 +0000
categories: jekyll update
usemathjax: true
---
While studying for the AP Physics C: Electricity & Magnetism Exam, I stumbled uopn the following problem

>Determine the electric field at point \\(P\\), which is located a distance \\(a\\) to the left
of a thin rod with a charge \\(+Q\\), uniform charge density \\(\lambda\\), and length \\(L\\)

The following is my approach to solving this problem:

$$
\vec{E}=k\int \frac{dq}{r^2}\hat{r} \Rightarrow \vec{E}=k\int \frac{dq}{x^2}(-\hat{i})
$$

$$
\lambda = \frac{Q}{L} = \frac{dq}{dx} \Rightarrow dq=\lambda dx
$$

$$
\Rightarrow \vec{E} = -k\hat{i}\int \frac{\lambda dx}{x^2}=-k \lambda \hat{i} \int_{a}^{a+L} \frac{1}{x^2} \, dx = k\lambda \hat{i} \left[ \frac{1}{a+L} - \frac{1}{a} \right] 
$$

I'm sure this expression simplifies further, but that is an exercise for another day.
