# Calling on all XRPL devs who are interested in Hooks:

We're working on "HookScript", a Typescript subset. Same syntax, but with some limitations (as it's compiled instead of interpreted - it needs to be efficient).

We plan on taking away the hard things that come with writing Hooks in C. A first version of HookScript will be familiar for JS/TS devs, but comes with a relatively limited SDK and quite some restrictions on what you can do (e.g. limited string operations, probably array/object limitations, etc.)

This is an open invitation to all of you to write a simple Hook in JS/TS syntax. Consider it pseudo code. It does not have to work -at all-. But it should showcase something simple you'd like to build with HookScript. And how you would like to build it.

Do not look for existing code: work on your own. Do you like objects? Methods, getters, setters? Would you push to an array? etc. Think of something relatively simple, and write your own code that resembles how you would like to build it if it would actually work.

Share the code with us with some inline comment on the What/Why... and I'll take it to the next meeting - as we're embarking on building a compiler :smile:

Here's an old example we posted on Twitter some time back: https://pbs.twimg.com/media/FdDLOCGWQAAYCmK?format=jpg&name=4096x4096

That syntax does not exist, and may in no way resembles what HookScript will actually be like. I'm looking for your own creativity and preferences so we have something to discuss.

## Keep It Simple

Final suggestion/request: keep it simple.

So think payment re-routing, auto NFT minting, memo sending and parsing, etc.
Think: simple state management: setting on chain key/value pairs based on input memos, reading them, and emitting transactions based on them later on. 

Do not think: typical complex DeFi stuff. Maybe a simple custody-hook based on state, but maybe that's already too much.

Keep it simple.  We much rather get a compiler ready that does the basic things amazingly well, but comes with restrictions we can work on later.

## And now what (how to submit an idea & code)?

- Create an issue
- Add an outline of your idea
- Add your code (e.g. inline, in triple backticks, or referring to a Gist / PR / ..)
