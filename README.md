# loadJS

LoadJS exists so you can write a small amount of JavaScript and link it on Twitter.

## To create a new link

Go to [tomhodgins.github.io/loadjs/new](http://tomhodgins.github.io/loadjs/new) to write JS to link on Twitter

## To load a link

Clicking a link generated by [tomhodgins.github.io/loadjs/new](http://tomhodgins.github.io/loadjs/new) will load that JavaScript on [tomhodgins.github.io/loadjs](http://tomhodgins.github.io/loadjs) and evaluate it on the page, as well as log the original JavaScript code to the console.

## Example

Entering the following JavaScript code into [tomhodgins.github.io/loadjs/new](http://tomhodgins.github.io/loadjs/new):

```
alert('Hello!')
```

Will generate the following tweetable URL:

```
http://tomhodgins.github.com/loadjs/#YWxlcnQoJ0hlbGxvIScp
```

You can share this link on Twitter, and when users click it, they will be taken to [tomhodgins.github.io/loadjs](http://tomhodgins.github.com/loadjs/#YWxlcnQoJ0hlbGxvIScp) where they will be greeted by an alert that says 'Hello!'.

## Why Did you Make This?

So I could link to bits of JavaScript on twitter (which shortens URLs) longer than 140 bytes.
