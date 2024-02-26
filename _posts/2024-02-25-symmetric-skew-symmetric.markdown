---
layout: post
title:  "Symmetric and Skew-Symmetric Matrices"
date:   2024-02-25 23:28:09 -0500
categories: math linear-algebra
---

I'm starting to publish these notes, for two main reasons:

1. I find myself revisiting these topics, especially when reading 3D vision papers, and Googling about them leads to weird SEO'd websites and secondly,
2. I enjoy writing in LaTeX, and I'd like to get better at it; especially now that [I no longer write longform](16831-latex-notes) LaTeX as part of coursework.

#### Context:

Symmetric matrices are matrices that have the property:

$$A = A^T \tag{1}$$

Skew-symmetric matrices on the other hand have a related but slightly different property:

$$A = -A^T \tag{2}$$


#### Property:

An interesting property that emerges as a consequence of this relationship, is that if a matrix $$A$$ is skew-symmetric, then its inverse, $$A^{-1}$$, is also skew-symmetric; i.e:

$$A^{-1} = -(A^{-1})^{T} \tag{3}$$


We can prove this from the above equation, and a familar property which is:

If $$A$$ is invertible, then (I'll show this proof in a future post):

$$(A^{-1})^{T} = (A^{T})^{-1} \tag{4}$$


Given this relationship, we can use Eq. $$(4)$$ in the RHS of Eq. $$(3)$$ to get:

$$-(A^{-1})^{T} = -(A^{T})^{-1}\tag{5}$$

And, since we established in Eq. $$(1)$$ that $$A$$ is skew-symmetric already we have:


$$-(A^{-1})^{T} = -(A^{T})^{-1} = -(-A)^{-1} = A^{-1}\tag{6}$$

Therefore proving Eq. $$(3)$$

I found this StackOverflow answer helpful [[1](stackoverflow-1)] while recollecting these topics.

[16831-latex-notes]: https://github.com/kshitijgoel007/16831-Spring-2022/commits/main/?author=SarthakJShetty
[stackoverflow-1]: https://math.stackexchange.com/a/368131

-Sarthak