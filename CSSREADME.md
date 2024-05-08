# CSS selectors

![computer with code](https://images.unsplash.com/photo-1523437113738-bbd3cc89fb19?q=80&w=1171&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

In CSS, selectors are used to target the HTML elements on our web pages that we want to style. There are a wide variety of *CSS selectors* available, allowing for fine-grained precision when selecting elements to style. In this article and its sub-articles we'll run through the different types in great detail, seeing how they work.
## What is a selector?
A **CSS selector** is the first part of a *CSS Rule*. It is a pattern of elements and other terms that tell the browser which HTML elements should be selected to have the CSS property values inside the rule applied to them. The element or elements which are selected by the selector are referred to as the subject of the selector.
```CSS
h1 {
    color: green;
    backgorund-color: pink;
}
p {
    color: orange;
}
```
## Selector lists
If you have more than one thing which uses the same CSS then the individual selectors can be combined into a selector list so that the rule is applied to all of the individual selectors. For example, if I have the same CSS for an *h1* and also a class of *.special*, I could write this as two separate rules.
```CSS
h1 {
    color: blue;
}
.special {
    color: blue;
}
```

## Types of selectors
Type selectors target an HTML element such as an *h1*:

```CSS 
h1 {

}
```
Class selectors target an element that has a specific value for its class attribute:
```CSS
.box{

}
```
**ID selectors** target an element that has a specific value for its *id attribute*:

```CSS
#unique {

}
```

For more on CSS Selectors, visit this MDN doc page: [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors#types_of_selectors)
