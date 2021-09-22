# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false ] `<div><span>hello</div></span>` <!-- the tags should be closed in the reverse order they were opened - so first </span> and then </div> -->

b) [ false ] <!-- the ul tag should be closed with </ul> -->

```html
<ul>
<li>one</li>
</ol>
```


c) [ false ] `<ul></ul><img/><ol><li>one</li></ol>` 
<!-- the <img> tag seems to be outside of any list or list element, we could reorder the tags as <ul><img/><ol><li>one</li></ol></ul> -->

## Q2 - What is a screenreader and why should we care about them?

<!-- A screen reader is a piece of assistive technology for visually impared people. HTML code should follow specific guidelines in order to be correctly read by the screen readers. Source: https://accessibility.its.uconn.edu/2018/08/22/what-is-a-screen-reader-and-how-does-it-work/ -->

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation 
<!-- <img> and other possible tags like <p>, <h1>, <h2>, etc for the titles of each picture -->

b) You want to create a website that lists all the art gallery websites in your city and links to their website. 
<!-- <ol> or <ul>, <li>, <a> and other possible tags like <p>, <h1>, <h2>, etc if you want to add paragraph descriptions for each art gallery -->

c) You want to sell designer hats. You need to receive orders from the user.
<!-- <button>, <a>, <select>, <option>, <img>, <form>, <input> and other possible tags like <p>, <h1>, <h2>, etc for text item description, ordering/shipping instructions, etc -->

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
<!-- No, because a button is a clickable element and it cannot have a descendant that is also a clickable element-->

## Q5 - What is the most generic tag you can use?
<!-- <div> -->

## Q6 - What do the following achronyms stand for?

a) `a` <!-- anchor for links on a website -->

b) `ol` <!-- ordered list-->

c) `ul` <!-- bullet point list-->

d) `li` <!-- list element -->

e) `tr` <!-- table row -->

f) `th` <!-- table head -->

g) `td` <!-- table data -->

## Q7 - Usually, `td` elements are children of what kind of elements?
<!-- td elements are children of tr elements-->

## Q8 - What is the difference between td and th?
<!-- td can be the child of any tr while th is usually the child of the first row indicating the header of the column-->

## Q9 - Which tag makes the text appear bigger: h1 or h3?
<!-- usually <h1>, if no modifications have been made to the CSS-->

## Q10 - In which situation can you use self closing tags?
<!-- when the element doesn't have any children <a />, <img />, <hr />, <br />, etc -->

## Q11 - What is autofilling and why is it important?
<!-- Autofilling is the function that fills in an input field automatically and it is important for reasons like speed, error correction and showing possible valid inputs to that field -->

## Q12 - Which attributes are always present in an img element?
<!--The img elements always contain an src attribute to point to the image location -->

## Q13 - Which attribute is always present for an anchor tag?
<!-- The anchor tags always have an href attribute to point to the website address-->
