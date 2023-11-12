# Read: Class 01

## Q 1. What is an HTML attribute?

`HTML` is a language made up of elements, which can be applied to pieces of text to give them different meaning in a document, structure a document into logical sections and embed content such as images and videos into a page. `HTML` attributes provide additional details or properties about the elements, and they are always included in the opening tag of an HTML element. Attributes consist of a name and a value, separated by an equal sign (=), and they are enclosed in double or single quotation marks. Common `HTML` attributes include **class**, **id**, **src**, **alt**, **width**, **height**, **style**, and many others, depending on the type of HTML element. 

## Q 2. Describe the Anatomy of an HTMl element.

The anatomy of an `HTML` element consists of various parts that define and structure the content within a web page. Such as: 

- Opening Tag: Example: `p`

- Element Content: Example: `<p>Hello, this is a paragraph.</p>`

- Closing Tag: Example: `</p>`

- Element: Example: `<p>Hello, this is a paragraph.</p>`

- Attribute: Example: `<a href="https://www.example.com">Link</a>`

- Attribute Value: Example: `href="https://www.example.com"`

## Q 3. What is the Difference between `article` and `section` element tags?

The `article` element is used to define a self-contained piece of content that could be distributed and reused independently, such as a news article, blog post, forum post, or a comment.

> Use <article> when you have a self-contained, distributable piece of content.

The `section` element is a more generic container used to group related content together. It doesn't inherently imply independence or reusability.

> Use <section> when you want to group related content together for organizational purposes.

## Q 4. What Elements does a “typical” website include?

A typical website includes essential HTML elements such as < head > for metadata, < body > for main content, headings (< h1 > to < h6 >), paragraphs (< p >), hyperlinks (< a >), images (< img >), lists (< ul >, < ol >, < li >), containers (< div >), and semantic HTML5 elements (< header >, < footer >, < nav >, < main >, < article >, < section >). Forms are represented by < form > and form input elements (< input >, < textarea >, < select >), and scripting is facilitated through the < script > element. These elements collectively structure and present content on a webpage.

## Q 5. How does metadata influence Search Engine Optimization?

Metadata influences SEO by providing information to search engines about a webpage's content. Key elements include the title tag for the page's headline in search results, the meta description for a brief summary, and meta robots to control indexing behavior. Well-optimized metadata enhances click-through rates, helps search engines understand content relevance, and indirectly impacts rankings.

## Q 6. How is the `meta` HTML tag used when specifying metadata?

The **<meta>** HTML tag is used in the **<head>** section to specify metadata. Common attributes include:

name: Defines the type of metadata.
content: Provides the actual metadata information.
> Example: <meta name="description" content="Brief summary of the page content"> for a meta description.

> # Miscellaneous

## How to start to design a Website.

### Q 1. What is the first step to designing a Website?

The first step to designing a website is to clearly define its purpose and goals. Understand the target audience, identify the key messages or content you want to convey, and determine the desired outcomes. This initial planning phase sets the foundation for making informed decisions about the website's structure, design, and functionality.

### Q 2. What is the most important question to answer when designing a Website?

One of the most important questions to answer when designing a website is: "What is the primary goal or purpose of this website?" Clarifying the website's objectives helps guide decisions regarding content, design, user experience, and functionality. Understanding the core purpose ensures that the design aligns with the intended outcomes and effectively serves the needs of the target audience.

## Semantics.

### Q 1. Why should you use an `h1` element over a `span` element to display a top level heading?

Using an `<h1>` element over a `<span>` element for a top-level heading is crucial for semantic structure, accessibility, and search engine optimization. `<h1>` is specifically designed for main headings, providing meaningful hierarchy and improving the clarity of the document's structure for both browsers and assistive technologies.

### Q 2. What are the benefits of using semantic tags in our HTML?

Using semantic tags in HTML improves accessibility, enhances SEO, provides a clear document structure for better readability and maintainability, ensures styling consistency, future-proofs the code, and increases interoperability with new technologies.

## What is JavaScript?

### Q 1. Describe 2 things that require JavaScript in the Browser?

> - Dynamic Content Updates: *JavaScript is commonly used to dynamically update and modify content on a webpage without requiring a full page reload. This dynamic behavior enhances user interactivity and responsiveness.*

> - User Input Handling: *JavaScript enables the handling of user interactions, such as form submissions, button clicks, and mouse events. It allows for real-time validation, feedback, and interaction without the need to reload the entire page.*

### Q 2. How can you add JavaScript to an HTML document?

**You can add JavaScript to an HTML document in three main ways:**

> Inline:

- `<button onclick="myFunction()">Click me</button>`

> Internal Script:

- `<script> function myFunction() { // JavaScript code } </script>`

> External Script: 

- `<script src="myscript.js"></script>`

> # Things I want to know more about

- I want to rearn more about GitHub and how to clone

- I wand to find out more about CSS