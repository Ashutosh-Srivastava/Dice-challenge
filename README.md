# Dice-challenge
## JavaScript and DOM(Document Object Model) used.

- Include the JS script tags at the end inside the body tag.

- JS uses camelCase. One can easily run the JS in the browser console. 
  - Right-click and inspect or Ctrl+Shift+I click on the console tab to run one line codes.
  - To create JS scripts: Sources -> Snippets -> +New snippet

- Use HTML Tree generator plugin in chrome browser to get the node hierarchy of HTML tags easily.

- We can use hierarchical selectors using a space between the two.

- Example HTML:
```
<ul id="list">
	<li class="item"><a href=https://google.com">Google</a></li>
	<li class="item">Second</li>
	<li class="item">Third</li>
</ul>
```

  - `document.querySelector("#list .item");`
     the result will be `<li class="item">..</li>`

  - `document.querySelectorAll("#list .item");`
     the result will be `NodeList(3) [li.item, li.item, li.item]`

- You can change the style using .style property followed by the CSS tag in camelCase without hyphen. refer this [link](https://www.w3schools.com/jsref/dom_obj_style.asp).

- Adding the class to a tag:
  - `.classList` returns the list of classes that are attached to that element.
  - `.classList.add(***class name in quotes***)`
  - `.classList.remove(***class name in quotes***)`
  - Instead you can use the `.toggle` for better scenario i.e. if the property is applied then remove it else vice-versa.

- innerHTML and textContent
  - `.innerHTML` gives everything inside the tag including nested tags
  - `.textContent` gives only the text inside the tags.

- Changing attribute of a tag:
  - `.setAttribute("***property name***","***new value***");`




