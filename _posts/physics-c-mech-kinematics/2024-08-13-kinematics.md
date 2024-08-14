---
layout: post
title:  Physics C Mechanics Kinematics - Notes
date:   2024-08-13 14:02:00 +0000
categories: jekyll update
usemathjax: true
---

Over my junior year of high school, I plan to self study AP Physics C: Electricity and Magenetism because my base school does not offer it. Although I am taking E&M's counterpart, Mechanics, during the school year, I thought it would be a good start to learn the Mechanics content before. Below is my take on taking notes for the kinematics unit.

# 2.1 - Instantaneous and Average Speed, Velocity, and Acceleration

First, we will begin learning kinematics in one-dimensional cases and then consider two dimensions.

Instantaneous velocity:

$$
v(t)=\lim_{ \Delta t \to 0 } \frac{\Delta x}{\Delta t}=\frac{dx}{dt}\iff \Delta x=\int dx = \int_{t_{1}}^{t_{2}} v(t) \, dt
$$

Instantaneous speed (magnitude of instantaneous velocity):

$$
|v(t)|
$$

Instantaneous acceleration:

$$
a(t)=\lim_{ \Delta t \to 0 } \frac{\Delta v}{\Delta t}=\frac{dv}{dt}=\frac{d^2x}{dt^2}\iff \Delta v=\int dv = \int_{t_{1}}^{t_{2}} a(t) \, dx 
$$

We can also define, for an \\(x(t)\\) function over some time interval \\((t_{1} \space \text{to} \space t_{2})\\), the average velocity as

$$
\text{Average velocity} = \bar{v}=\frac{\int_{t_{1}}^{t_{2}} dx}{t_{2}-t_{1}} = \frac{x|^{t_{2}}_{t_{1}}}{t_{2}-t_{1}}=\frac{x(t_{2})-x(t_{1})}{t_{2}-t_{1}} = \frac{\Delta x}{\Delta t} 
$$

The numerator \\(\Delta x\\) is called the ***displacement***, the net difference in the location of an object independent of its path to get there.

We can use the same approach for the average speed

$$
\text{Average speed} = \frac{\int_{t_{1}}^{t_{2}} |dx|}{t_{2}-t_{1}}=\frac{\text{total distance}}{\Delta t} 
$$

Unlike displacement, total distance is the distance travelled irrespective of direction. Thus we can say that the total distance \\(\geq\\) displacement. If the path is in a single direction in a straight line then total distance \\(=\\) displacement, if not, total distance \\(\geq\\) displacement.

We can also take the same approach for the average acceleration

$$
\text{Average acceleration} = \bar{a} = \frac{\int_{t_{1}}^{t_{2}} a(t) \, dt}{t_{2}-t_{1}} = \frac{\int_{t_{1}}^{t_{2}} \frac{dv}{dt} \, dt}{t_{2}-t_{1}} = \frac{\int_{t_{1}}^{t_{2}} \, dv}{t_{2}-t_{1}} = \frac{v|^{t_{2}}_{t_{1}}}{t_{2}-t_{1}} = \frac{v(t_{2})-v(t_{1})}{t_{2}-t_{1}} = \frac{\Delta v}{\Delta t}
$$
