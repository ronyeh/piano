# Piano + JavaScript

This tutorial demonstrates shows how to create a basic piano in JavaScript. All code on this page is MIT licensed. The source code [can be found here](https://github.com/ronyeh/piano/tree/main). The source code for this website [can be found here](https://github.com/ronyeh/piano/tree/gh-pages).

[Here is a demo](https://squarepoet.github.io/piano/v1) of what we will build together.

The NPM package for this library is: [https://www.npmjs.com/package/go-piano](https://www.npmjs.com/package/go-piano).

## Audio

First, we will need to play individual notes from our virtual piano. We can use a JS library for this. Here are two that are easy to use:

-   [Musical](https://github.com/PencilCode/musical.js)
-   [Tone](https://tonejs.github.io/)

```js
// Tone JS
// Play a middle 'C' for the duration of an 8th note
piano.triggerAttackRelease("C4", "8n");

// Musical JS
piano.tone("C", 1.0, 0.5);
```

## Graphics

Let's make some graphics for our piano. We will use SVG to draw the keys and body of the piano. If you want to skip this step, you can download an image of a piano.

```js
alert("Hello World");
```

## Interaction

Now we need to let the user interact with the piano, through the mouse and keyboard (or through tapping on a touch screen).

```js
alert("Hello World");
```

### See

-   [JS Guitar](https://guitar.js.org/)
-   [JS Music Theory](https://music.js.org/)
