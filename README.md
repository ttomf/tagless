# Tagless

This is simple web page created without (almost) any HTML tag for [Tagless Hackclub event](https://tagless.hackclub.com/). Only used tag is `<style>`, the whole page is just CSS!

It's optimized for the desktop browser, on phone it might not work.

## How this works

Browser adds `<html>` and `<body>` tags even if they aren't in the HTML file, so only tag I wrote is the `<style>` tag.

For text, I use `::before` and `::after` pseudo-elements with `content` property. I use JetBrains Mono Nerd font because it has icons.

Because of that, I had only `html`, `html::before`, `html::after`, `body`, `body::before` and `body::after` elements, so the page is not very impressive.

## Generative AI Disclosure

No generative AI was used to write anything in this project. I only used ChatGPT for learning about CSS tricks.
