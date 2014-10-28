---
layout: post
title: Day 25&colon; Mr Fisher's Notes
---

As I missed this meeting for a conference, Mr Fisher took notes. (Thank you, Mr Fisher!)
I copy his notes directly below:

<hr />

My handwriting leaves something to be desired, so I will try to type out what went on in today's class.

1. Benson presented 6.2
2. Herington presented 6.1
3. Stuffelbeam presented 6.5
4. Hawkins presented an algorithm for \\(t=n-2\\), and proved it by induction


Benson's 6.2:  ABCD is a rhombus and angle A is congruent to angle B.  She then
drew diagonal BD, which is congruent to itself.  She then used proposition 8 to
show that triangle DAB is congruent to triangle DCB, and the corresponding parts
of the triangles are equal. Thus angle ABC (being made up of two equal angles equal
to the two equal angles making up CDA) is congruent to CDA. This shows all the
angles of the rhombus are congruent, and by the definition of a rhombus all sides
are congruent. ABCD is regular.  There were no objections.

Herington's 6.1: An equilateral triangle is equiangular, hence regular.  By way
of contradiction, supposed that angle A is greater than angle B or angle C.  By
proposition 19, angle A must be subtended by a greater side.  Hence CB would be
greater than AB and AC, which is a contradiction (ABC is an equilateral triangle).  
Similarly, angle B and angle C cannot be greater than the other angles.  
Thus, angle A,B, and C must be congruent to one another.  With all the sides and
angles congruent to one another, ABC is regular.

Stuffelbeam's 6.5: Given a regular pentagon, ABCD, we draw AC and AD.  By
proposition 4, triangle ACB is congruent to triangle ADE. Since these triangles
are congruent, their bases are congruent (which are AC and AD). Thus triangle ACD
is isosceles (the base of triangle ACD is DC, with sides AC and AD congruent).

     **We briefly debated whether or not you have to prove that triangle ACD
     isn't equilateral, but we decided that since equilateral triangles are isosceles
     it would perhaps be insignificant at the moment.**

Hawkin's T=n-2 Algorithm: (this could be a bit hard to explain)

Pick a ray.  Do not draw a ray that:

    1. Goes outside the polygon (at all)
    2. Crosses another diagonal
    3. Passes through a point that is not an endpoint

To check and see if you can draw a diagonal (to divide the polygon into triangles),
the first time around you draw an eligible ray at every other vertex (skipping one).
Once you get back to the starting vertex, you skip two vertices (this is the second
"loop").  You continue this, skipping 1 more vertex each time ("loop").  You
stop when the number of vertices being skipped is equal to the total number of
vertices. This should split up any polygon into triangles by using only eligible
diagonals.  

His proof by induction was stated orally during the closing seconds of class, and
he stated that for any n-gon, if you had one side you add one triangle.  So for
n=3 you have 1 triangle. Add a side and you now have n=4 with 2 triangles, and so on.  
