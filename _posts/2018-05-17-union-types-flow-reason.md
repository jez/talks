---
layout: post
title: "Union Types in Flow & Reason"
date: "2018-05-17"
---

Union types are powerful yet often overlooked. At work, I'd noticed that using
union types in Flow incurred a creeping cost in terms of a bloated bundle size.

In this talk, I explore why that's the case. We starts with a problem which
union types can solve, flesh out the problem to motivate why union types are
definitely the solution, then examine the resulting cost of introducing them. In
the end, we compare Flow to other compile-to-JS languages on the basis of how
they represent union types in the compiled output. I'm especially excited about
Reason, so we talk about it the most.

- [Union Types in Flow & Reason](../slides/union-types-flow-reason/union-types-flow-reason.pdf)
- [Markdown sources (GitHub)](https://github.com/jez/talks/tree/master/slides/union-types-flow-reason)
