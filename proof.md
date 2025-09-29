# A short visual proof of the Pythagorean Theorem

1. Assume a right-angled triangle $\triangle ABC$ with the right angle at vertex $B$.
2. Let $D$ be the foot of the perpendicular from $B$ to the hypotenuse $AC$.
3. The two smaller triangles partition the larger triangle, which means their areas sum to the area of the whole: $[\triangle ABC] = [\triangle ADB] + [\triangle BDC]$.
4. Now $\triangle ABC$ is similar to $\triangle ADB$ and also to $\triangle BDC$:
    - $△ABC \sim △ADB$ since they share angle A, and both have right angles
    - $△ABC \sim △BDC$ since they share angle C, and both have right angles
5. The ratio of the area $[\triangle ABC]$ to $|AC|^2$ is the same as the ratio of $[\triangle ADB]$ to $|AB|^2$, as well as the ratio of $[\triangle BDC]$ to $|BC|^2$ since:
    - For similar triangles, the ratio of areas equals the square of the ratio of corresponding sides.
6. Using these ratio equalities, the equation from step 3 translates to $|AC|^2 = |AB|^2 + |BC|^2$.

![Illustration](./proof.drawio.svg)

([Here](./proof-gpt5mini.md) is a more detailed version of this proof (expanded and polished by GPT 5 mini))