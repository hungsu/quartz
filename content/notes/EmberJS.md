---
title: "EmberJS"
---
![Ember Octane](https://emberjs.com/images/tomsters/octane750w-7d2b2a06bb1ba5c5dd1e3ad03dd5a873.webp)

A framework for making [Single page apps](notes/SPA). Popularised a [UI engineering](notes/UI%20engineering) technique called [data down, actions up](notes/Data_down_action_up).


EmberJS was made in a highly opinionated way that favours convention over configuration, and learning these conventions is the most difficult part for UI engineers new to Ember. In particular, [Rock and roll with Ember](https://balinterdi.com/rock-and-roll-with-emberjs/) comments that Ember's Routing conventions are the hardest to learn.

## How Ember works

Like other frameworks, Ember is made up of many parts. This includes:

- A live reload server
- [[Ember CLI]], which is how the server is started and how routes are added to an Ember app
- [Ember Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi), a browser extension for Chrome
- [[QUnit]] for testing

### Ember's unique versioning

Ember has a concept called Ember Editions, where major shifts in philosophy  are marked with a name. These are distinct from [[Semantic Versioning]]. In Ember, a Major version change means APIs were removed.
 
[[Ember Octane]] is the first named Ember Edition, and began with Ember 3.15

Anyone migrating from Classic to Ember Octane might like the [ember-octane-vs-classic-cheat-sheet/](https://ember-learn.github.io/ember-octane-vs-classic-cheat-sheet/)

## Ember's routing conventions

Routing that is highly opinionated, using [[router.js]] and some conventions on URL schemes.


## More Ember

Official [website](https://emberjs.com/)

[The Official EmberJS Blog](https://blog.emberjs.com/) Includes posts from The Ember Times, as well as major releases of EmberJS.

[[Honeypot]] made a [25 minute documentary about Ember](https://youtu.be/Cvz-9ccflKQ)

[^1]: [State of JS 2021 Libraries changes over time](https://2021.stateofjs.com/en-US/libraries/tools_arrows)