# Movie Card - v1 (Basic)

This is the first version of my Movie Card project, built in class as an 
introduction to HTML and basic CSS styling.

## Tags & concepts used

- `<!DOCTYPE html>` — tells the browser this is an HTML5 document
- `<html>` — the root element wrapping the whole page
- `<head>` — holds page info that isn't visible content (title, meta tags)
- `<meta charset="UTF-8">` — sets character encoding so text displays correctly
- `<meta name="viewport">` — makes the page responsive on different screen sizes
- `<title>` — sets the browser tab title
- `<style>` — internal CSS written directly inside the HTML file
- `<center>` — used to center the content on the page (old/deprecated tag, learned this later)
- `<body>` — contains everything visible on the page
- `<h1>` — main heading ("Movie Card Example")
- `<div>` — a container used to group the card's contents together
- `<img>` — displays the movie poster image, with `height`, `width`, `src`, and `alt` attributes
- `<h2>` — sub-heading for the movie title
- `<p>` — paragraph text for the rating and genre
- `<button>` — clickable "Book Tickets" button

## CSS used

- `text-align: center` — centers text inside an element
- `border` — adds a visible border around the card
- `width` — sets a fixed width for the card
- `padding` — adds spacing inside the card, between the border and content
- `background-color` — sets the card's background color

## Screenshot

![v1 basic movie card](screenshot.png)

## What I'd improve next

This version uses one plain `<div>` styled directly by its tag name, a solid 
red background, and the deprecated `<center>` tag. In v2, I learned to use 
classes, flexbox, shadows, and hover effects to make it look more modern.
