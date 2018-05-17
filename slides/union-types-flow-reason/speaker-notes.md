# Union Types in Flow & Reason

- Thank you for being here!

- First time talking at Stripe (and to non-students)!
  - Nice thing about talking to students is everyone has the same background!

- Please stop me at any time!
  - I love explaining things from a different angle.

- I'm pretty satisfied with Flow.
- One of the features of Flow I think about most? -> union types

# Union types are Powerful!


## Union Types: An Example

Double check: are people familiar with union types?

Question: what have people used union types for in the past?


# Union types in Flow have a cost :(


## Outline


## Union Types in a React Component


## We can model this with a union type


## Initial Feedback? Add a "cancel" button


## `needsCancelButton`: Initial Implementation


## Adding a `'FailureScreen'`


## Oh no! A bug!


## First reaction: just fix the bug.


## `switch`: Taking Advantage of Exhaustiveness


## Takeaway: Only use union types with `switch`!


## Correctness, but at what cost?


## Correctness, but at what cost?


## Correctness, at the cost of bundle size!


# Types and Optimizing Compilers


## Types promise better compiled code.


## Flow is not a compiler


## Enter: Reason


## `needsCancelButton` in Reason


## Reason looks pretty familiar!


## Reason's Generated Code


## Reason's Generated Code + `uglify`


## Safety AND Performance


# Bonus: Comparing Other Languages


## TypeScript


## PureScript


## Elm


## Further Reading




<!-- vim:tw=60
-->
