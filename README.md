# HTML Basics

## Getting Started

HTML is the language of the web, so, as a user of the web, it’s the language you have spent the majority of your time with, whether you knew it or not. Now we’re going to take a closer look at how it works.

## What We'll Cover

1. The parts and functions of an HTML tag
2. Using opening and closing HTML tags
3. How to structure an HTML document

## Anatomy of an HTML Tag

The fundamental building block of HTML is a __tag__. Tags allow web developers to tell things to the browser like "make this text a header" or "include this image". Tags all follow the same format like this:

```html
<tag-text>
```

It's just some text wrapped in __<__ and __>__ characters. The most basic tag is the "break" tag. This is represented in HTML as `<br>` and tells the browser to create a new line. Over the next few lessons, we are going to create a simple profile page for a brand-new Flatiron student.

<iframe height='265' scrolling='no' title='intro br' src='//codepen.io/joemburgess/embed/MoJLVL/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/MoJLVL/'>intro br</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Go ahead and add in more `<br>` tags and see what happens.

## Opening and Closing Tags

While the break tag is very useful, the first thing we really need for our profile page is a header. Good news—there’s a tag for that! It's the `<h1>` tag. This will make the text larger and bolder, and make it the most clearly important text on the page. Obviously, we don't want all of our text as a header. To tell the browser which text should be a header, and which shouldn't, we use closing tags. Closing tags are just exactly the same as tags you've seen before but prefixed with a /. The closing tag for `<h1>` would be `</h1>`. Take a look at this in acton:

<iframe height='265' scrolling='no' title='closing tags' src='//codepen.io/joemburgess/embed/BZpMPJ/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/BZpMPJ/'>closing tags</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Any text you put between the `<h1>` and `</h1>` will be a header. Great, right?

Most HTML tags work just like this:

1. Opening tag, which states what kind of tag we’re using;
2. The text we want the tag to be applied to;
3. Closing tag, which makes sure the tag is limited to a certain piece of text.

So when we talk about “what kind of tag we’re using,” what are our options? How many HTML tags are there? There are a lot! Another useful example is the __paragraph__ tag which is represented with a `<p>`. The paragraph tag tells the browser the text in between it is a paragraph and puts two new lines above and below the text.

<iframe height='265' scrolling='no' title='p tag' src='//codepen.io/joemburgess/embed/owBmQL/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/owBmQL/'>p tag</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

When we’ve put all these pieces together—opening tag, content, closing tag—we now have a larger piece we call an HTML __element__.

## Document Structure

While most of writing HTML is writing tags like the ones above, there are some special tags that tell the browser about what's coming up. These are tags that are never seen by users, but the browser uses them to understand the external resources your web page needs. Here is a full example of a web page:

<iframe height='265' scrolling='no' title='Intro to HTML' src='//codepen.io/joemburgess/embed/jwydYp/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/jwydYp/'>Intro to HTML</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

You'll notice that the web page looks identical to the one above. If you look at the code you will see three new tags: `<html>`, `<head>`, and `<body>`. You might have also spotted these tags in the last lesson when we looked under the surface of flatironschool.com and peeked at the HTML underneath. That’s because these three tags are in every single webpage. Here’s what they do:

* The `<html>` tag tells the browser "hey contained in here is a bunch of HTML code."
* The `<head>` tag we don't really use just yet, but it will contain our references to outside bits of code such as CSS or Javascript.
* The `<body>` tag tells the browser "contained in here is the stuff I actually want you to show the user."

In many future examples, we will omit these html, body and head tags due to brevity. Be sure to remember them when you create your own websites though!

## Summary

Congratulations! Now you know how we build __HTML__. All HTML uses __tags__, and most tags come in pairs of an __opening tag__ and a __closing tag__. There are a lot of existing HTML tags we can use to display text on webpages, such as `<h1>` `</h1>` and `<p>` `</p>`. A set of HTML tags with enclosed content is an HTML __element__. We use the `<html>`, `<head>` and `<body>` tags to define our overall HTML __document structure__.

## Key Terms to Review

* HTML tag
* HTML element

## Helpful Resources

* [HTML Dog HTML Tags](http://www.htmldog.com/references/html/tags/)
* [Mozilla Developer Network HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

## What’s Next

All right, now we’re rolling with HTML. Let’s add something more interesting. Go on to the next lesson to see how we can start pulling images into our webpages.