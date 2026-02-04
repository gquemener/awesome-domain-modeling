# Awesome Domain Modeling

## Introduction

Modeling is the act of building a simplification of a reality in order to solve a problem. Too simple and it will not solve the problem, too complex and it will become the new problem. A day-to-day example is a map. Tons of different kinds of maps exist (world map, city map, bicycle map, maritime map, subway map), and each is aiming to solve a very specific problem. Every version intentionaly omits details and a single map containing all those informations would most likely be unreadable and require an extensive amount of effort to use!

> [!NOTE]
> Whether you’re _modelling_ or _modeling_, you’re doing the same thing. The only difference is in the spelling—the one with the single L is preferred in the United States, while the one with two Ls is preferred everywhere else. [Source](https://www.grammarly.com/blog/modeling-or-modelling/)

Domain Modeling is a technic aiming to resolve a business problem through the design of a set of small, well-shaped, models, collaborating with each others, based on the discovery and understanding of a (sub-)domain.

It is closely related to Domain-Driven Design and is part of the Tactical side of this approach.

It is NOT related to any language, framework or paradigm.

Other modeling technics includes "data-driven modeling" (focusing on database table structure), "class-driven modeling" (for UML based projects) or even [God Object](https://en.wikipedia.org/wiki/God_object) (which can be compared to the multi-purposes map that was described at the beginning of this section).

## Books

- [Domain Modeling Made Functional: Tackle Software Complexity with Domain-Driven Design and F# - Scott Wlaschin](https://pragprog.com/titles/swdddf/domain-modeling-made-functional/)
- [Effective Aggregate Design - Part I: Modeling a Single Aggregate - Vaughn Vernon](./docs/vernon_2011_1.pdf)
- [Effective Aggregate Design - Part II: Making Aggregates Work Together - Vaughn Vernon](./docs/vernon_2011_2.pdf)
- [Effective Aggregate Design - Part III: Gaining Insight Through Discovery - Vaughn Vernon](./docs/vernon_2011_3.pdf)

## Articles

- [Domain Model Pattern - Udi Dahan](https://udidahan.com/2007/04/21/domain-model-pattern/)
- [Anemic Domain Model - Martin Fowler](https://www.martinfowler.com/bliki/AnemicDomainModel.html)
- [Doctrine ORM - Adding behavior to Entities](https://www.doctrine-project.org/projects/doctrine-orm/en/3.2/tutorials/getting-started.html#adding-behavior-to-entities)
- [What time can teach us about models - Stijn Vannieuwenhuyse](https://aardling.eu/en/insights/what-time-can-teach-us-about-models)

## Videos

- [Domain Modelling - Yves Reynhout - DDD Europe 2019](https://www.youtube.com/watch?v=tjiuDQbkRFY) 19:14
- [Making impossible state impossible - Richard Feldman](https://www.youtube.com/watch?v=IcgmSRJHu_8) 25:05
- [Event Sourcery : A video course that covers the fundamentals of reactive systems and event sourcing, both theoretical and practical - Shawn McCool](https://www.youtube.com/playlist?list=PLQuwqoolg4aI6v1GvtRg3NgT0PBBHVqii) approx. 04:00:00 (the six first videos give a very good idea of what building blocks are available)

## Katas
- [Tell don't ask : A legacy refactor kata, focused on the violation of the tell don't ask principle and the anemic domain model.](https://github.com/racingDeveloper/tell-dont-ask-kata)
