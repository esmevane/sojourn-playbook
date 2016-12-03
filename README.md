# Sojourn Playbook

## Notes

* Node has a pretty good idea: extreme modularity.
* Unfortunately it's become a mess, with time.
* Massive library and tool fragmentation is paralyzing.
* Massive product churn is fatiguing.
* Sometimes things aren't even well documented.
* We started making boilerplates to avoid days of configuration and research.
* But now there are hundreds of slightly different boilerplates.
* It's a new level of fatigue - which to start with?
* Even when you choose, how do you understand the tools?
* What exactly are you using at any given time?
* I've done it, too.
* But the real value isn't in having a boilerplate.
* It's in explaining how to set a project up.
* In how to make the complexities obvious to everyone.
* I've decided to not do another iteration of my boilerplate, Sojourn.
* Instead I'm going to build a new boilerplate from scratch.
* While I'm doing it, I'll journal my way through.
* The result, will be the Sojourn Playbook.

## The Goals

* Set up a development server by hand
* Establish a development, test and production build
* Create a SPA on the front-end, with code-splitting
* Use some plain old javascript object patterns to glue things together
* Wire up react, redux and a pleasant front-end
* Keep everything strongly typed, and use good lint processes too

## Not Goals

* In-depth, but not a step-by-step tutorial
* Policies can change, not trying to find the best way, just *a* way


## Main tools

* Webpack (PostCSS, Font-Awesome, Babel)
* React (React Router)
* Redux (Redux Saga, Immutable)
* Mocha (Chai, maybe Karma)
* Express or Koa?
* Typescript?  Flow?  Some strong typing mechanism.
