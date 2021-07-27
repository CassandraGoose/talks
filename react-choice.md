

# React
### and the Paradox of Choice

<div class="top-bar-content">
DenverScript - 27 July 2021
</div>

Notes:
talking a bit about an aspect of FE development that i feel has influenced my burnout in the past. this talk is meant to be a way to start a discussion started on developer experience

I'm picking on React today, but the conepts that I'm referencing apply to all of frontend.

---

### Hi!

<div class="top-bar-content">
intro
</div>

Notes:
I'm Cassandra, you can call me Cass! 
I've worked professionally in React, Vue, Angular 4, various backend technologies and on many different projects as a consultant. I'm picking on React today, but the conepts that I'm referencing apply to all of frontend.

For me, this constant decision-making me had me exhausted by the end of the day. I can't imagine how the newer devs on my team were feeling.
On projects in the past, I experienced a lot of buyer's remorse.
One project sticks out as positive, even if I felt irratated by all the rules in the beginning. It's the best functioning app that I've worked on and also the prettiest. My lead has many clear expectations about the code and he _stuck_ to them and could justify them. (This is why I'm talking to you today)
checkout the code for some basic examples

---

I read this book...

![old man yells at cloud meme](https://i.kym-cdn.com/entries/icons/original/000/019/304/old.jpg)
<!-- .element: class="fragment" -->

<div class="top-bar-content">
the research...
</div>

Notes:
- paradox of choice by barry schwartz

- there needs to be more research to back up the findings of the book and also we need to take into context because overchoice might not be as pervasive as we think or may be more likely to affect only certain aspects of life 
- so take everything here with a grain of salt

Paradox of Choice
- choice and freedom are important for well-being
- too much choice can negatively impact our well-being
- Author uses a collection of studies to back this up, I'm waiting to see more modern research but there are some other people that discuss choice
- one main study is: TODO
- talk about maximizers

not going to read you the studies, but will provide a gist to a bunch of links

---

- Overchoice (or choice overload)
- Tyranny of Small Decisions
- Analysis Paralysis
- Buyer's Remorse

<div class="top-bar-content">
the research...
</div>

Notes:
- Overchoice is a cognitive impairment in which making a decision becomes overwhelming due to the many potential outcomes and risk. More replicated studies are needed to verify that this is a thing.
- Tyranny of Small Decisions is an essay that explores the concept that a number of decisions, individually small and insignificant in size and time cumulative result in a larger and significan't outcome which is undersierable. 
- Overanalyzing or overthinking can lead to no decision being made.
- Buyer's remorse is a cognitive dissonance in which a person makes a difficult decision between similar alternatives but regrets their decision for any reason (and the reasons often have nothing to do with the quality of their decision) (Can often be caused or increased by worrying that other people may question the decision or claim to have a better alternative)
- Consider these issues for a seasoned dev, and then a newer one. How are they supposed to be successful in their learning?

---

People _do_ need choice and autonomy in order to be healthy mentally - but maybe not so many choices.

<div class="top-bar-content">
the research...
</div>

---


Too much choice may promote burnout, feelings of overwhelm, motivation issues, learning difficulties, etc.

The current technology for web development potentially requires too many decisions.

<div class="top-bar-content">
the concern...
</div>

---


Decisions to make when setting up a React project and day-to-day code-writing:

<div class="big-list">
Folder structure? PWA? Redux vs MobX vs Context? Bundling? Server-side rendering? Create react app or another toolchain? Typescript? Style preprocessor? CSS library? JSS? File naming conventions? Forms validation helper? Sagas or Thunks?
CSS naming conventions? Axios vs Fetch? Proptypes? Classes vs hooks? Binding? HOCs? Inner component layout? Dumb vs smart components? Renderless components? Services? Naming conventions? Code layout? All other JS style options?
How to actually solve the problem?
</div>

<div class="top-bar-content">
the concern...
</div>

---

Embrace Good enough software
<!-- .element: class="fragment" -->

Discuss rules and opinions up front
<!-- .element: class="fragment" -->

Setup a detailed eslint and prettier!
<!-- .element: class="fragment" -->


<div class="top-bar-content">
possible solutions
</div>

Notes:
When reading The Pragmatic Programmer, one of the big takeaways for me was writing good enough software... because perfection is not possible anyways and we'll just pull our hair out.
Tacking on the airbnb eslint rules won't suffice.

eslint: extend off of this: https://github.com/facebook/create-react-app/blob/main/packages/eslint-config-react-app/index.js
extra things to add : 
- (no classes) https://github.com/tatethurston/eslint-plugin-react-prefer-function-component#readme
- order of methods: https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/sort-comp.md
- https://www.npmjs.com/package/eslint-plugin-folders 
- BEM https://stylelint.io/
- CSS modules: https://www.npmjs.com/package/eslint-plugin-css-modules
- https://eslint.org/docs/rules/class-methods-use-this (for breaking out methods into services)
- https://github.com/WebbyLab/eslint-plugin-more/blob/master/docs/no-then.md

---

Use opinionated frameworks

Notes: Next.js

<div class="top-bar-content">
possible solutions
</div>

---

meditate

<div class="top-bar-content">
possible solutions
</div>

---

Consider developer experience:
- Avoid maximization when making decisions
- Decide on rules and opinions and enforce them


<div class="top-bar-content">
take-aways
</div>
Note: Byeeeeeee

---

Thanks!

- [Gist of Resources](https://gist.github.com/CassandraGoose/de55440f795dd6eda77d4e9c9b499cb7)
