# The-Maximum-Number-of-Sides-in-the-Intersection-of-Two-Unit-Regular-Polygons
We developed a formula to calculate the answer of the problem in the name of this repository.

This solved a problem presented by Peter Kagey: For integers $n,m\ge3$, let $K(n,m)$ be the largest possible number of sides of the intersection of a unit-side-length regular $n$-gon and a unit-side-length regular $m$-gon, under arbitrary rigid motions and with nonempty interior. What is $K(n,m)$ ?

We didn't discover any "beautiful theory" behind this problem, because many corner cases must be handled carefully. But our formula allows one to compute $K(n,m)$ in $O(n)$ when $n\le m$.

A necessary python certificate is also presented here.
