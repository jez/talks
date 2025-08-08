---
layout: post
title: "Refactoring Stubborn, Legacy Codebases"
date: 2024-11-19T00:00:00-08:00
---

I gave a talk together with [G. D. Ritter] at QCon SF 2024, relating to work
we've done together at [Stripe](https://jez.io/thoughts/on-stripe/).

The abstract of the talk:

> At Stripe, we manage a codebase of tens of millions of lines of Ruby. Like any
> large codebase, people have no shortage of complaints about it, and it's our
> job to fix those complaints. Fixing them means refactoring the problems away,
> and over the years we've learned what it takes for these sweeping refactors to
> be successful: it comes down to leverage and ratcheting.
>
> We'll use two examples to talk about what it means to have leverage over a
> codebase and how to ratchet increment progress: how we built a Ruby type
> checker to make developers happier, and how we're building a Ruby package
> system to introduce modularity. The ideas will be high-level, and apply to
> basically any team that wants to run a migration in a large, stubborn
> codebase.

- [Video](https://www.infoq.com/presentations/refactoring-legacy-codebases/)
- [Slides](https://sorbet.run/talks/QCon2024/)
- [Talk page](https://qconsf.com/presentation/nov2024/refactoring-stubborn-legacy-codebases)

[G. D. Ritter]: https://gdritter.com/
