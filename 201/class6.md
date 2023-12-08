# Problem Domain, Objects, and the DOM

# JavaScript Object Basics

## Q 1. How would you describe an object to a non-technical friend you grew up with?

It's like a digital Swiss army knife that holds different pieces of information or functionalities. 

## Q 2. What are some advantages to creating object literals?

1) **Simplicity**: Object literals provide a straightforward way to organize and represent data with a simple syntax.

2) **Readability**: They make the code more readable, as properties and values are defined in a clear key-value pair format.

3) **Flexibility**: Objects can hold various data types and structures, offering flexibility in organizing and storing information.

4) **Ease of Use**: Convenient for creating ad-hoc structures without the need for formal class definitions.

5) **Rapid Prototyping**: Ideal for quick prototyping and experimentation due to their concise and expressive nature.

## Q 3. How do objects differ from arrays?

> ***Objects:***

- Use key-value pairs to store and access data.

- Keys are strings or symbols.

- Ideal for representing real-world entities and their properties.

> ***Arrays:***

- Use numerical indices to organize elements.

- Elements are accessed by their position in the array.

- Suited for ordered collections of similar items, like a list.

## Q 4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

Bracket notation is typically used when the property key contains special characters, starts with a number, or when the key is dynamic (determined at runtime).

## Q 5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?

- The this keyword is used to refer to the current object (dog in this case) within the method humanAge.

- this.name refers to the name property of the current dog object.

- this.age refers to the age property of the current dog object.

- The use of this allows the method to dynamically reference properties of the current object (dog). If the object's properties change, the method will still reference the correct values.

[JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

# Introduction To The DOM

## Q 1. What is the DOM?

The DOM (Document Object Model) is a programming interface that represents a structured document (typically HTML or XML) as a tree of objects, allowing dynamic manipulation of a web page's content, structure, and style using languages like JavaScript. 

## Q 2. Briefly describe the relationship between the DOM and JavaScript.

The DOM (Document Object Model) and JavaScript have a close relationship in web development. JavaScript is a scripting language commonly used to interact with the DOM. The DOM serves as a representation of the document's structure, and JavaScript allows developers to dynamically manipulate this structure, update content, respond to user actions, and create interactive web pages. JavaScript functions as the bridge between the static content of a web page and the dynamic, interactive experience that users expect.

[Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

[How to Solve Programming Problems](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

[What’s the Difference Between Primitive Values and Object References in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)