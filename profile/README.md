## Hi there 👋

This is ai.fn(), a service to use AI chat completions as a regular Javascript function in any project, for both browser and Node.JS

See more at [https://aifn.run](https://aifn.run)

## Motivation

ChatBot integrations and REST API's have their own boilerplate and set up, which has to be done over and over again.

Javascript already offers the tools we need to make that easier: `async/await` combined with `ES module imports`.

Not only that, with AI completions we can achieve many tasks using simple prompts, encapsulated as Javascript functions.

## Here's an example

```js
import ai from 'https://aifn.run/ai.mjs'
const lorem = await ai.fn('Create a lorem ipsum paragraph with {count} words');
const paragraph = await lorem({ count: 100 });
```
