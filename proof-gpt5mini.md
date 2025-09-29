A very short intuitive proof of the Pythagoras theorem

1. Let ABC be a right triangle with the right angle at B. Let D be the foot of the perpendicular from B to the hypotenuse AC (so D lies on the segment AC and BD ⟂ AC).

2. Observe the three right triangles ABC, ADB and BDC. Triangle ADB has a right angle at D and shares angle A with ABC, so by AA (angle–angle) similarity we have

    - ABC ~ ADB.

    Similarly, triangle BDC has a right angle at D and shares angle C with ABC, so

    - ABC ~ BDC.

    Thus all three triangles are pairwise similar.

3. From the similarity between ABC and ADB the corresponding sides are in proportion. Matching angles gives the correspondence $A\leftrightarrow A$, $B\leftrightarrow D$, $C\leftrightarrow B$, so the side $AC$ (opposite the right angle at $B$ in $\triangle ABC$) corresponds to $AB$ (opposite the right angle at $D$ in $\triangle ADB$). Similarly, from the similarity between $\triangle ABC$ and $\triangle BDC$ we get the correspondence $A\leftrightarrow B$, $B\leftrightarrow D$, $C\leftrightarrow C$, so $AC$ corresponds to $BC$.

4. Area scales with the square of a linear scale factor for similar figures. Hence

    $\dfrac{[ADB]}{[ABC]} = \left(\dfrac{AB}{AC}\right)^2$, and

    $\dfrac{[BDC]}{[ABC]} = \left(\dfrac{BC}{AC}\right)^2$.

    Equivalently

    $\dfrac{[ABC]}{AC^2} = \dfrac{[ADB]}{AB^2} = \dfrac{[BDC]}{BC^2}$,

    where $[T]$ denotes the area of triangle $T$.

5. The big triangle's area is the sum of the two smaller ones: $[ABC] = [ADB] + [BDC]$. Divide both sides by $AC^2$ and use the equal ratios from step 4:

    $1 = \dfrac{AB^2}{AC^2} + \dfrac{BC^2}{AC^2}$.

    Multiply through by $AC^2$ to obtain the Pythagorean relation

    $AC^2 = AB^2 + BC^2$.

6. Remarks: the cancellation in step 5 requires the triangle to be nondegenerate (area $>0$); this is automatic for a genuine right triangle. If the triangle were degenerate the identity is trivial.

## References

- Wikipedia — Pythagorean theorem, section “Proofs using similar triangles”: https://en.wikipedia.org/wiki/Pythagorean_theorem#Proofs_using_similar_triangles

### Note on equivalence

The argument in this file uses area-scaling for similar triangles (area ratios scale with the square of linear ratios). Textbooks often present the closely related proportional-side form obtained directly from similarity:

- From similarity one gets $\dfrac{AB}{AC}=\dfrac{AD}{AB}$, hence $AB^2=AC\cdot AD$.
- Similarly $\dfrac{BC}{AC}=\dfrac{DC}{BC}$ gives $BC^2=AC\cdot DC$.

Adding these two equalities yields

$AB^2+BC^2=AC(AD+DC)=AC^2$.

This is algebraically equivalent to the area-based presentation in the main text; both rely on the same triangle similarities and differ only in whether one uses areas (scaling by the square of the scale factor) or direct side proportions as the primary step.

![Illustration](./proof.drawio.svg)