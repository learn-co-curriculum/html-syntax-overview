# Introduction to HTML

HTML is the language you have spent the majority of your time with as a user of the internet. This is because HTML is the language of the web. Everything else you've ever heard of around web programming boils down to just modifying HTML and it's close sibling: CSS. We'll get into CSS in a bit, but for now let's investigate HTML.

The fundamental building block of HTML is what's called a _tag_. Tags allow web developers to tell things to the browser like "make this text a header" or "include this image". Tags all follow the same format like this:

```html
<tag-text>
```

It's just some text wrapped in `<` and `>` characters. The most basic tag is the "break" tag. This is represented in HTML as `<br>` and tells the browser to create a new line. Over this lesson and into CSS we are going to create a simple Profile page.

<iframe height='265' scrolling='no' title='intro br' src='//codepen.io/joemburgess/embed/MoJLVL/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/MoJLVL/'>intro br</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Go ahead and add in more `<br>` tags and see what happens. Go ahead and...break it down

![Break it down](https://curriculum-content.s3.amazonaws.com/web-development/break-it-down.gif)

### Open and Close Tags

While the break tag is very useful, what if our designer says we need a header. There is a tag for that. It's the `<h1>` tag. This will make the text much larger and bold. Obviously, we don't want all of our text as a header. To tell the browser which text should be a header, and which shouldn't we use _closing tags_. Closing tags are just exactly the same as tags you've seen before but prefixed with a `/`. The closing tag for `<h1>` would be `</h1>`. Here is an example

<iframe height='265' scrolling='no' title='closing tags' src='//codepen.io/joemburgess/embed/BZpMPJ/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/BZpMPJ/'>closing tags</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Any text you put between the `<h1>` and `</h1>` will be a header. There are many many other tags like this. Another great example is the paragraph tag which is represented with a `<p>`. The paragraph tag tells the browser the text in between it is a paragraph and puts two new lines above and below the text. Here is an example:

<iframe height='265' scrolling='no' title='p tag' src='//codepen.io/joemburgess/embed/owBmQL/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/owBmQL/'>p tag</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### Document Structure

While most of writing HTML is writing tags like the ones above, there are some special tags that tell the browser about what's coming up. These are tags that are never seen by users, but the browser uses them to understand the external resources your web page needs. Here is a full example of a web page

<iframe height='265' scrolling='no' title='Intro to HTML' src='//codepen.io/joemburgess/embed/jwydYp/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/jwydYp/'>Intro to HTML</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

You'll notice that the web page looks identical to the one above. If you look at the code you will see three new tags: `<html>`, `<head>`, and `<body>`. The `<html>` tag tells the browser "hey contained in here is a bunch of HTML code". The `<head>` tag we don't really use just yet, but it will contain our references to outside bits of code such as CSS or Javascript. Finally, the `<body>` tag tells the browser "contained in here is the stuff I actually want you to show the user". 

In many future examples, we will omit these `html`, `body` and `head` tags due to brevity. Be sure to remember them when you create your own websites though!
