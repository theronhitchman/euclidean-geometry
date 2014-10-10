---
layout: post
title: Fisher Goes Inside
---

We had another deep discussion about definitions today, as Mr Fisher led us through
his ideas for defining the "inside" and "outside" of a polygon. As is to be expected,
this took a long time to work through, but we eventually sharpened the language to
this:

> **Definition:** (Fisher) Let P be a polygon and let X be a point not lying on
> any of the sides of P. Choose a ray r with initial point X which does not pass
> through a vertex of P. Let \\(n\\) be the number of sides of P which meet r.
> If \\(n\\) is odd, we say that X is inside P. If \\(n\\) is even, we say X is
> outside P.

The initial version had us checking _every_ ray r. Mr Walters pointed out that this
would make the definition very hard to check. But if it worked for every ray then
it would be a very powerful tool. After a bit of talking, I set this problem for you:

> **Conjecture R:** Let P be a polygon and let X be a point not lying on one of the sides
> of P. Given a ray r with initial point X which does not pass through a vertex of P,
> let \\(n(r)\\) be the number of sides of P which meet r.
>
> If \\(n(r)\\) is even (odd) for some ray r, then it is even (respectively odd) for
> every allowed ray r.
