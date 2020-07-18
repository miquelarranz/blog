---
title: Why Typescript?
date: "2020-07-18T19:18:03.284Z"
description: "Why everyone is using Typescript nowadays? Why should I use it too?"
---

I'm pretty sure that all of you have heard about Typescript, but what it is? Basically, Typescript is a superset of Javascript, but, in the end, it's Javascript too but with some cool features:

1. It adds typing to Javascript, which is super useful to add robustness to our code and avoid easy type mistakes. Also, it will help us to improve the semantic and the readability of our code.

2. It Can be used on both sides of the force (client/server). So you can use it in your React projects but also in the NestJS ones.

3. It has support for the Javascript of the present and the future before they become supported by modern browsers (Chrome, Firefox, ~~IE~~, Safari). So we use that last stuff and forget about compilation steps.

4. It can be compiled to a Javascript (we already said it's Javascript) version that works everywhere. So, your Typescript code will always be compiled to a compatible Javascript version that, as we said, works with all the modern browsers.

Let's see an example of code:

```
// Random Class

class Table {
    private _width: number;

    constructor(width: number) {
        this._width = width;
    }

    get id() {
        return this._id;
    }
}

// Random code that uses our class
const table = new Table(12);
console.log(table.width) // will return 12
```

There are more features but I wanted to mention the most important ones. So, what are waiting to give it a try?
