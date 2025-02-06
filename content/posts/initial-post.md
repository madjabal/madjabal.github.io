---
date: 2025-02-05
title: "Initial Post"
draft: false
math: true
---

This is an initial post to test this setup while I flesh out the ideas for this website.

Edit: here's some math:

Inline math can be written like this: $x^2 + y^2 = z^2$

Display math should be on its own line:

$$
\begin{align*}
\nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
\nabla \times \mathbf{B} &= \mu_0\left(\mathbf{J} + \epsilon_0\frac{\partial \mathbf{E}}{\partial t}\right)
\end{align*}
$$

Edit: even more math:

Using custom vector macros: $\vx + \vy = \vz$

A numbered equation:

$$
\begin{equation}
\mat{A}\vx = \lambda\vx
\label{eq:eigenvalue}
\end{equation}
$$

Reference the equation using \eqref{eq:eigenvalue}.

Using probability macros:
$$
\begin{equation}
\prob(\vx \in A) = \expect[\mathbf{1}_A(\vx)]
\label{eq:prob}
\end{equation}
$$

Using norm macro: $\norm{\vx}$

Integration with custom diff:
$$
\begin{equation}
\int_a^b f(x) \diff x = F(b) - F(a)
\label{eq:integral}
\end{equation}
$$