---
title: "Home"
---

This is the homepage of my website!

Testing $\int e^x \, dx = e^x$.

See [](https://doi.org/10.1137/23M1585210).

Wiki reference: [ghost forest](wiki:Ghost_forest) or see
<wiki:Ghost_forest>.

## mp4 video: controls only appear by right-clicking

<video controls
  src="./videos/RC3000_animation_80m_100km2.mp4">
  Your browser does not support the video tag.
</video>

% this works no better:
%:::{figure} ./videos/RC3000_animation_80m_100km2.mp4
%Comparison of ALE3D and mfluid on 3000 m radius crater
%:::

## Testing latex with equation labels:

The assumptions above allow expressing the velocity
in the Airy solutionas in terms of a potential function as
$\vec u = \nabla\Phi$ (i.e. $(u,w) = (\Phi_x,\Phi_z)$),
with $\Phi(x,z,t)$ satisfying
\begin{equation}\label{Phi1}
\begin{split}
\nabla^2\Phi &= 0, \qquad -h_0\leq z \leq \eta(x,t),\\
\Phi_t &= 0, \qquad z=-h_0,\\
\Phi_{tt} + g\Phi_z&= 0, \qquad z = 0.
\end{split}
\end{equation}
The second equation comes from the solid bottom boundary.
Once $\Phi$ has been computed, the velocity is given by the gradient, while
the free surface is determined by
\begin{equation}\label{Phieta}
\eta(x,t) = -\frac 1 g  \Phi_t(x,0,t)
\end{equation}
The third equation of (\ref{Phi1}) comes from the free surface condition
$\eta_{tt}(x,0,t) = w(x,0,t)$, the vertical component of the velocity vector.

