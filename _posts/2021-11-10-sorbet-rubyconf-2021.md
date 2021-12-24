---
layout: post
title: "Compiling Ruby to Native Code with Sorbet and LLVM"
date: 2021-11-10T00:00:00-08:00
---

At [Stripe](https://jez.io/thoughts/on-stripe/) I spent two years working on
the [Sorbet Compiler], an ahead-of-time compiler for Ruby powered by
[Sorbet](https://sorbet.org), the type checker for Ruby. Along with Trevor
Elliott, I spoke about the Sorbet Compiler at RubyConf 2021 in Denver, Colorado.

The abstract of the talk:

> At Stripe, "make it faster!" is one of our most requested features, but we
> don't want to have to pause work on other features to get speed. Instead,
> we've built an ahead-of-time compiler for Ruby, powered by Sorbet and LLVM,
> focusing on improving latency in Stripe's multi-million line Ruby code base.
>
> In this talk, we'll cover why we built it, how it works, and share preliminary
> results from compiling Stripe's production Ruby code. It's not quite ready for
> prime time yet, but we're interested in sharing our approach and getting early
> feedback on the design.
>
> <p></p>

- [Video](https://www.youtube.com/watch?v=BH8S1htcHXY)
- [Slides](https://sorbet.run/talks/RubyConf2021/)
- [Talk page](https://rubyconf.org/program/sessions#session-1171)

[Sorbet Compiler]: https://github.com/sorbet/sorbet/tree/master/compiler
