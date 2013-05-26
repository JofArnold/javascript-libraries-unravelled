# Behind CoffeeScript

Since using CoffeeScript (to be forever called CS from hereon in) I've become progressively lazier in my attempts to understand the JavaScript (JS) behind it all. To avoid brain rot, I started a scratch pad where I'd reverse-engineer and explain to myself the JS that's spat out. Then I thought - maybe it's useful to other people.

So… As and when I see something interesting in my compiled JS files, I hope to add it here with an explanation of exactly how it works. I plan to go into the fundamentals as much as possible.

The pages are hosted on the wiki pages of this repo:

- ####[Syntax](https://github.com/JofArnold/behind-coffeescript/wiki/syntax)
- ####Classes *(coming soon)*
- ####Idioms *(coming soon)*

## Todo:

Please feel free to make comments and amend. This is a work in progress and I've not necessarily checked all the code compiles and is free of typos.

- Explain `constructor` and `extends`
- Explain loops and comprehensions, in particular the brackets in `count = (num for num in [10..1])`