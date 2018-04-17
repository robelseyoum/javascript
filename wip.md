# Modify Styles, Attributes, and Classes in the DOM

## Attributes

element.setAttribute()
element.getAttribute()
element.hasAttribute() // bool
element.removeAttribute()

## Classes

// get class
element.className;
element.getAttribute('class');
element.setAttribute('class', 'new'); // warning, this will override all existing classes

// set class
element.className = 'open';

element.classList.add('open');
element.classList.add('open', 'blue');
element.classList.remove('open');
element.classList.toggle('open');

## Styles

element.setAttribute('style', 'padding: 10px 0;')
element.style.color = 'red';
element.styke.background-color = 'blue';

# Understanding Events in JavaScript

onclick
onmouseover
onmouseout
hover

