# JavaScript Libraries Unravelled

With the arrival of CoffeeScript and CoffeeScript source maps, it's now possible to code sophisticated applications without touching a single line of JavaScript. No doubt some people are pretty happy with that, but there's probably a few who will still want to get under the hood and understand what's going on behind all this magical obfuscation.

I'm one such person and as a recent coding exercise I started recreating common libraries functions from scratch; I found it really useful to clarify my understanding. My aim is to add snippets as I go about my daily work and explain each snippet from first principles in a way that would allow someone fairly new to programming JavaScript to understand.

I hope this is useful to someone! Let me know if you'd like me to delve into a particular library or method.

**Tip**: understanding JavaScript's `call` and `apply` is critical to getting to the bottom of many of these functions. The best explanation I've seen is [Yahuda Katz'](https://github.com/wycats) excellent blog post [Understanding JavaScript Function Invocation and “this”](http://yehudakatz.com/2011/08/11/understanding-javascript-function-invocation-and-this/) - I strongly recommend it.


### CoffeeScript

- [Fat arrow,`=>`](https://github.com/JofArnold/javascript-libraries-unravelled/wiki/CoffeeScript-Fat-Arrow)
- [Array manipulation](https://github.com/JofArnold/javascript-libraries-unravelled/wiki/CoffeeScript-Array-Manipulation)

### Underscore

- `_.bind` *[coming soon]*
- `_.bindAll` *[coming soon]*



## Todo

Please feel free to make comments and amend. This is a work in progress and I've not necessarily checked all the code compiles and is free of typos.

- CoffeeScript `extends`
- CoffeeScript loops and comprehensions, in particular the brackets in `count = (num for num in [10..1])`
- Start tackling jQuery