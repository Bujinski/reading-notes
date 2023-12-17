# Object-Oriented Programming, HTML Tables

# Domain Modeling

## Q 1. Explain why we need domain modeling.

Domain modeling is a crucial step in software development that involves creating a conceptual representation of the problem domain. The problem domain refers to the subject area or the specific aspect of the real world that the software aims to address. Domain modeling is important for several reasons:

1. Establishes a shared understanding and vocabulary.

2. Clarifies requirements and identifies ambiguities.

3. Breaks down complex problems for easier comprehension.

4. Guides the design process by providing a foundation.

5. Simplifies problem-solving through abstraction.

6. Supports adaptability to changes in the problem domain.

7. Facilitates communication between technical and non-technical stakeholders.

8. Serves as valuable documentation for reference and knowledge transfer.

> [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

# HTML Table Basics

## Q 1. Why should tables not be used for page layouts?

Using tables for page layouts is discouraged because it goes against semantic HTML, poses accessibility challenges, hinders responsiveness, complicates maintenance, impacts page load performance, has SEO implications, limits adaptability to future technologies, and results in less readable code. Modern web development favors CSS-based layouts for cleaner, more efficient design.

## Q 2. List and describe 3 different semantic HTML elements used in an HTML `<table>`.

`<thead>` (Table Head):

Represents the header section of a table. Typically contains one or more rows with header cells (`<th>`), providing labels for the columns or groups of columns in the table. It helps organize and identify the content in the table's header.
`<tbody>` (Table Body):

Encloses the main content of the table, containing rows with standard data cells (`<td>`). This element separates the table's header from the data, contributing to a cleaner structure. It is especially useful for large tables with data spanning multiple rows.
`<caption>` (Table Caption):

Provides a title or caption for the entire table. It is an optional element that can be placed just before or after the `<table>` tag. The `<caption>` element is valuable for describing the purpose or context of the table, adding accessibility and clarity to the content.

> [HTML table basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

# Introducing Constructors

## Q 1. What is a constructor and what are some advantages to using it?

A constructor is a special method in object-oriented programming that is automatically called when an object is created. It is used to initialize the object's state and perform any necessary setup.

> Advantages of using constructors:

1) Initialization: Constructors initialize the object's state and provide a way to set initial values for its attributes.

2) Encapsulation: Constructors help encapsulate the initialization logic within the class, making it easier to manage and understand the code.

3) Default Values: Constructors can have default values for parameters, allowing for flexibility in object creation.

4) Code Reusability: Constructors can be used to create multiple instances of the same class with different initial states, promoting code reusability.

5) Consistency: Constructors help ensure that an object is in a valid state upon creation, reducing the chances of errors during the program's execution.

## Q 2. How does the term `this` differ when used in an object literal versus when used in a constructor?

- In an object literal, `this` refers to the global object or the object that triggered an event.

- In a constructor function, `this` refers to the newly created instance of the object.

> [JavaScript object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

# Object Prototypes Using A Constructor

## Q 1. Explain prototypes and inheritance via an analogy from your previous work experience.

Imagine a dental office where dentists have a set of standard procedures (like cleaning, filling cavities, etc.) listed in a manual. The manual represents the prototype. Each patient's specific dental record is like an instance, storing unique information.

Now, imagine a new dentist joining. They get a copy of the manual, which is like inheriting from the prototype. The new dentist can perform procedures following the manual and customize the treatment based on the patient's specific record.

> In this analogy:

- The manual is the prototype, representing shared methods or procedures.

- Each patient's record is an instance, storing individual data.
The new dentist inherits from the manual, gaining access to standard procedures and customizing them based on each patient's needs.

- This mirrors how prototypes and inheritance work in JavaScript, where objects can inherit properties and methods from prototypes, while maintaining their unique data.

> [A Beginner's Guide to JavaScript's Prototype](https://ui.dev/beginners-guide-to-javascript-prototype)