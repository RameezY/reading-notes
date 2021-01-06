# CSS Notes
CSS is a way to style elements you have in your HTML.  It makes your webpages look great, because at first you had your foundation in HTML, but now you're decorating the inside of the foundation.

The great thing about CSS is that you can have two paragraphs but have each one looking different from eachother.  Each element in HTML can have its own rules and styling.

Here are some important rules to keep in mind:
If you have a single HTML page, you can place the CSS code in the head section of that HTML page.

However, if you have multiple HTML pages, it is recommended to have a separate CSS file that you can use to apply it to all the HTML pages.

CSS structure is as follows:
```css
p {
    color: black;
    text-align: center;
}

The P is the selector which is referring to the HTML element <p> followed by the property and values inside "{}". Each property is ended by a ":" followed by a value for example "black" and then that is ended with a ";" and you can have multiple properties inside a single {} for that specific element.
```
The above example will apply it to all HTML paragraph elements.  However, you can also get even more specific and detailed.  For example if you wanted to apply one styling to all the paragraph but have one specific paragraph have a different styling, that is also possible.  You would need to assign an ID to the HTML paragraph element, and then in CSS mention that ID and apply a styling where it will only be applied to that specific paragraph.  

Example:
```html
<p id=1>This paragraph was assigned the ID of "1"</p>
```
In CSS:
```css
#1 {
    color: red;
}

This has the p selector followed by the id I assigned it in the HTML for it and will only apply that styling to that specific paragraph.
```

Overall, the selector in CSS is similar to what it is in HTML without the < >, with the exception of some added ones.  For example:
Applying styling to every single element on the page:
```css
*
```

Applying styling to specific ID:
```css
#followedbytheID
```

### Table of Contents
* [Reading Notes Home](README.md)
* [Growth Mindset](growth_mindset.md)
* [Markdown Reading](markdown.md)
* [Coders Computer](coders_computer.md)
* [Git Notes](git_notes.md)
* [HTML Notes](html_notes.md)
* [CSS Notes](cssnotes.md)
* [What I Have Learned So Far](learned_so_far.md)