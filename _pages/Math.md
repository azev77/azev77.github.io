---
permalink: /Math/
title: "Math"
excerpt: "Math"
author_profile: true
---

Eigenvalues and Eigenvectors of general linear functions
=
Take a vector space $V$ over a field $F$.
<br/>
Let $T: V \to V$ be a linear function, that is
$T\left(\alpha v + \beta w \right) = \alpha T\left( v \right) + \beta T\left( w \right)$ for $\alpha, \beta \in F, v,w \in V$.
<br/>
An 
**eigenvector** is a vector $v \in V$ 
and an 
**eigenvalue** is a scalar $\lambda \in F$ 
such that 
$T(v) = \lambda v$. 
<br/> 
The fixed points of a linear function are the eigenvectors corresponding to the eigenvalue $\lambda =1$.
<br/> <br/>
**Example**: eigenvectors/eigenvalues of the derivative operator
<br/>
The derivative operator $D: C^{\infty} \to C^{\infty}$ 
over the vector space of smooth functions over the field of real numbers is a linear function:
<br/>
$D\left(\alpha f + \beta g \right) = \alpha D\left( f \right) + \beta D\left( g \right)$ for $\alpha, \beta \in \mathbb{R}, f,g \in C^{\infty}$
(verify this).
<br/>
**Proposition**: 
the set of eigenvalues of $D$ is  $ \left( \lambda \in \mathbb{R}  \right) $
and
the correspoding set of eigenvectors of $D$ is $ \left(  f(t)=f_0 e^{\lambda t}, f_{0} \in \mathbb{R}  \right)$.
<br/>
**Proof**: 
<br/>
$\Rightarrow$ it is straightforward to verify that 
$D(f) = \lambda f$ for $\lambda \in \mathbb{R}$ and $f(t)=f_0 e^{\lambda t}$.
<br/>
$D(f) = f'(t) = \lambda f_0 e^{\lambda t} = \lambda f(t)$ $\blacksquare$.
<br/>
$\Leftarrow$
Suppose there exists a function $g(t) \neq f_0 e^{\lambda t}$ 
such that $D(g) = \lambda g$.
<br/>
Then $g'(t) = \lambda g(t)$
<br/>
Then: 
<br/>
$$
\begin{align*}
D\left( g(t) e^{-\lambda t} \right) &= g'(t) e^{-\lambda t} + (-\lambda)g(t) e^{-\lambda t} & \text{product rule}
\\
                                    &= \lambda g(t) e^{-\lambda t} + (-\lambda)g(t) e^{-\lambda t} & \text{we assumed } g'(t) = \lambda g(t)
\\
                                    &= 0                                                           & \text{algebra} 
\end{align*}
$$
<br/>
$\Rightarrow$ $D\left( g(t) e^{-\lambda t} \right) = 0$
<br/>
$\Rightarrow$ $g(t) e^{-\lambda t} = c $
<br/>
$\Rightarrow$ $g(t) = c e^{\lambda t} $
which contradicts our assumption that $g(t) \neq f_0 e^{\lambda t}$ $\blacksquare$.
<br/>
It follows that the fixed points of the differential operator take the form 
$f(t)=f_0 e^{t}$.


More examples at [this link](http://people.math.gatech.edu/~meyer/MA6701/module18.pdf).




 
