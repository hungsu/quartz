---
title: "EmberJS"
---
![Ember Octane](https://emberjs.com/images/tomsters/octane750w-7d2b2a06bb1ba5c5dd1e3ad03dd5a873.webp)

A framework for making [Single page apps](notes/SPA). Popularised a [UI engineering](notes/UI%20engineering) technique called [data down, actions up](notes/Data_down_action_up).


## Why Ember over other frameworks like React, Vue, and Svelte? 

Things admittedly look bad for Ember right now. According to [State of JS 2021](https://2021.stateofjs.com/en-US/libraries/front-end-frameworks/front_end_frameworks_experience_ranking), only 21% of people who used Ember would choose to use it again:

![[StateofJS_2021_satisfaction.png]]

So why choose Ember?

- CrowdStrike uses it, and they're an astonishingly good place to work. 

For more detail, [[I built the same app in Svelte, Vue, and Ember in 2022]]

## How to start learning Ember

EmberJS was made in a highly opinionated way that favours convention over configuration, and learning these conventions is the most difficult part for UI engineers new to Ember. In particular, [Rock and roll with Ember](https://balinterdi.com/rock-and-roll-with-emberjs/) comments that Ember's Routing conventions are the hardest to learn.


## How Ember works

Like other frameworks, Ember is made up of many parts. This includes:

- A live reload server
- [[Handlebars templating]] for HTML components
- [[Ember CLI]], which is how the server is started and how routes are added to an Ember app
- [Ember Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi), a browser extension for Chrome
- [[QUnit]] for testing
- [[RouterJS]] and some conventions
- [[Ember Data]] for state management

## Ember's conventions


Introduces nesting
```handlebars
<UiFiles::MyComponent />
```



Component arguments (props in VueJS)
```handlebars
<MyComponent @answer={{42}} />
```

Community generally dislikes Watching or Observing data


### Routing and file hierarchies

### Ember Editions and major versions

Ember has a concept called Ember Editions, where major shifts in philosophy  are marked with a name. These are distinct from [[Semantic Versioning]]. In Ember, a Major version change means APIs were removed.
 
[[Ember Octane]] is the first named Ember Edition, and began with Ember 3.15

Anyone migrating from Classic to Ember Octane might like the [ember-octane-vs-classic-cheat-sheet/](https://ember-learn.github.io/ember-octane-vs-classic-cheat-sheet/)

The next Ember Edition will be named Polaris, and has not yet released as of 2022-07-29, Ember 4.6.

## More Ember

Official [website](https://emberjs.com/)

[The Official EmberJS Blog](https://blog.emberjs.com/) Includes posts from The Ember Times, as well as major releases of EmberJS.

[[Honeypot]] made a [25 minute documentary about Ember](https://youtu.be/Cvz-9ccflKQ)

[^1]: [State of JS 2021 Libraries changes over time](https://2021.stateofjs.com/en-US/libraries/tools_arrows)