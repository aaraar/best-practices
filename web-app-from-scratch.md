# Best Practices for WAFS

## Don't Repeat Yourself (DRY)
Your code should not repeat itself multiple times. When you have two pieces of code that are very similar, ask yourself how the code could be written in a dynamic, DRY way.

[Example](https://stackoverflow.com/a/31218286/5440366)

## Put your `<script src="script.js"></script>` tag before the closing tag `</body>`
I you place your script tag in the head of your document, you could run into problems where your Javascript is rendered earlier than your HTML.

## Keep the Global Scope clean
