---
layout: post
title: "Math Rendering Test"
---

Let’s test some inline math first: the Cauchy–Schwarz inequality says that  
$\lvert \langle f, g \rangle \rvert \leq \lVert f \rVert_2 \, \lVert g \rVert_2$.

Now let’s try a display equation:

$$
\int_{\Omega} \lvert \nabla u(x) \rvert^2 \, dx
  = -\int_{\Omega} u(x) \, \Delta u(x) \, dx
$$

We can also test a more complicated expression:

$$
e^{i\pi} + 1 = 0, \quad
\text{and} \quad
\hat{f}(\xi) = \int_{\mathbb{R}^n} f(x)e^{-2\pi i \langle x, \xi \rangle} \, dx
$$

And finally, a small system of equations:

$$
\begin{cases}
-\Delta u = f & \text{in } \Omega, \\
u = 0 & \text{on } \partial \Omega.
\end{cases}
$$
---
_Posted on November 9, 2025._