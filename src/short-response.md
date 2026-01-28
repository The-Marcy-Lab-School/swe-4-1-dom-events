# Short Response Questions

Answer the following questions in 2-4 sentences each. Be specific and use vocabulary from the lessons. Your responses will be evaluated out of 6 points. You can earn 3 points for writing quality and 3 points for the accuracy and precision of the technical content.

## Question 1: Loading JavaScript

A student places their `<script src="index.js">` tag in the `<head>` of their HTML file. Their JavaScript code uses `document.querySelector('#my-button')` but it returns `null` and their code breaks. Explain why this happens and what the browser is doing when the script runs. What should they do to fix this error?

**Your Answer:**


## Question 2: Event Delegation

Imagine you are building an e-commerce site that has a grid of 100 product cards that are created dynamically. You want each product card to highlight when clicked. You can either add a click listener to each individual card or use event delegation. 

1. First, explain what event delegation is.
2. Then, explain the tradeoffs of adding a click listener to each individual card and using event delegation.

**Your Answer:**


## Question 3: event.target vs event.currentTarget

You add a click listener to a `<div>` element. Inside that div, there's a `<button>`. When a user clicks the button, both `event.target` and `event.currentTarget` are logged. Explain what each property represents in this scenario and why they might be different.

**Your Answer:**

## Question 4: querySelector Returns null

A student writes 

```js
const button = document.querySelector('#my-button');
button.addEventListener('click', () => {
  //...
})
``` 

Their code crashes with an error `"Cannot read property 'addEventListener' of null."` Explain
1. what `null` means in this context
2. why `querySelector` might return `null`
3. what the student should check to fix this issue.

**Your Answer:**

## Question 5: Draw the DOM

The DOM is described as a "tree-like" structure. Take a look at the following `html` content:

```html
<html>
  <head>
    <title>Hello World</title>
  </head>
  <body>
    <h1 id='heading'>Heading</h1>
    <section>
      <p class='text'>Paragraph</p>
    </section>
  </body>
</html>
```

Using pen and paper or a digital tool, create a diagram with a box for each element and lines connecting them to show the parent-child relationships. Then, take a screenshot or a photo and add it to this `src/` directory.

For inspiration, see the diagram here: https://marcylabschool.gitbook.io/marcy-lab-school-docs/mod-4-interactive-web-applications/1-intro-to-interactive-pages
