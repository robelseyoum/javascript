# JavaScript and the DOM

# Document Object Model

## [Introduction to the DOM](https://www.digitalocean.com/community/tutorials/how-to-traverse-the-dom)

- [What is the DOM](https://www.digitalocean.com/community/tutorials/introduction-to-the-dom#what-is-the-dom)
- [The Document Object](https://www.digitalocean.com/community/tutorials/introduction-to-the-dom#the-document-object)
    - `document`
- [The Difference Between the DOM and HTML Source Code](https://www.digitalocean.com/community/tutorials/introduction-to-the-dom#what-is-the-difference-between-the-dom-and-html-source-code)

## [Understanding the DOM Tree and Nodes](https://www.digitalocean.com/community/tutorials/understanding-the-dom-tree-and-nodes)

- [HTML Terminology](https://www.digitalocean.com/community/tutorials/understanding-the-dom-tree-and-nodes#html-terminology)
    - tag, 
    - attribute 
    - value 
    - text
- [The DOM Tree and Nodes](https://www.digitalocean.com/community/tutorials/understanding-the-dom-tree-and-nodes#the-dom-tree-and-nodes)
    - parents
    - siblings
    - children
- [Identifying Node Types](https://www.digitalocean.com/community/tutorials/understanding-the-dom-tree-and-nodes#identifying-node-type) 
    - element
    - text
    - comment
    - document
- [Modifying the DOM with Event](https://www.digitalocean.com/community/tutorials/understanding-the-dom-tree-and-nodes#modifying-the-dom-with-events)
    - `addEventListener()`


## How to Access Elements in the DOM

- [Accessing Elements by ID](https://www.digitalocean.com/community/tutorials/how-to-access-elements-in-the-dom#accessing-elements-by-id)
    - `getElementById()`
- [Accessing Elements by Class](https://www.digitalocean.com/community/tutorials/how-to-access-elements-in-the-dom#accessing-elements-by-class)
    - `getElementsByClassName()`
- [Accessing Elements by Tag](https://www.digitalocean.com/community/tutorials/how-to-access-elements-in-the-dom#accessing-elements-by-tag)
    - `getElementsByTagName()`
- [Query Selectors](https://www.digitalocean.com/community/tutorials/how-to-access-elements-in-the-dom#query-selectors)
    - `querySelector()`
    - `querySelectorAll()`

## [How to Traverse the DOM](https://www.digitalocean.com/community/tutorials/how-to-traverse-the-dom)

- [Root Nodes](https://www.digitalocean.com/community/tutorials/how-to-traverse-the-dom#root-nodes)
    - `document`
    - `document.Element` 
    - `document.head` 
    - `document.body`
- [Parent Nodes](https://www.digitalocean.com/community/tutorials/how-to-traverse-the-dom#parent-nodes)
    - `parentNode`, `parentElement`
- [Children Nodes](https://www.digitalocean.com/community/tutorials/how-to-traverse-the-dom#children-nodes)
    - `childNodes`, `firstChild`, `lastChild`, `children`, `firstElementChild`, `lastElementChild`
- [Sibling Nodes](https://www.digitalocean.com/community/tutorials/how-to-traverse-the-dom#sibling-nodes)
    - `previousSibling`, `nextSibling`, `previousElementSibling`, `nextElementSibling`

## [How to Make Changes to the DOM](https://www.digitalocean.com/community/tutorials/how-to-make-changes-to-the-dom)

- [Creating New Nodes](https://www.digitalocean.com/community/tutorials/how-to-make-changes-to-the-dom#creating-new-nodes)
    - `createElement()`
    - `createTextNode()`
    - `node.textContent`
    - `node.innerHTML`
- [Inserting Nodes into the DOM](https://www.digitalocean.com/community/tutorials/how-to-make-changes-to-the-dom#inserting-nodes-into-the-dom)
    - `node.appendChild()`
    - `node.insertBefore()`
    - `node.replaceChild()`
- [Removing Nodes from the DOM](https://www.digitalocean.com/community/tutorials/how-to-make-changes-to-the-dom#removing-nodes-from-the-dom)
    - `node.removeChild()`
    - `node.remove()`
    
