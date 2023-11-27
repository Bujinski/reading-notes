# Images, Color, Text

# HTML Media

## Q 1. What is a real world use case for the `alt` attribute being used in a website?

The alt attribute in HTML provides alternative text for images, ensuring accessibility for visually impaired users and aiding SEO. It also improves user experience in cases of slow internet or image loading failure. Compliance with web standards is maintained by including descriptive alt text.

> - `<img src="example.jpg" alt="A beautiful sunset over the mountains">`

## Q 2. How can you improve accessibility of images in an HTML document?

Include a concise and descriptive alt attribute for each image.

> - `<img src="example.jpg" alt="Friends enjoying a picnic in the park">`

If an image is decorative, use an empty alt attribute.

> - `<img src="decorative-border.png" alt="">`

Opt for responsive images that adapt to different devices.

> - `<img src="responsive-image.jpg" alt="Example of a responsive image">`

For complex images, use captions or linked long descriptions.

> - `<figure><img src="complex-chart.png" alt="Sales chart for Q3 2023"><figcaption>Sales chart for Q3 2023</figcaption></figure>`

## Q 3. Provide an example of when the `figure` element would be useful in an HTML document.

The `<figure>` element is useful when associating an image with a caption or additional content, such as charts, diagrams, or illustrations, enhancing semantic structure and accessibility.

## Q 4. Describe the difference between a `gif` image and an `svg` image, pretend you are explaining to an elder in your community.

A GIF image is like a traditional picture that can move, similar to a short animated clip. It's like a small, simple video. On the other hand, an SVG image is like a drawing made with lines and shapes that can be scaled to any size without losing quality, just like a digital coloring book. GIFs move, SVGs are like resizable drawings.

## Q 5. What image type would you use to display a screenshot on your website and why?

For displaying a screenshot on a website, it's advisable to use a PNG image. PNG supports lossless compression, preserving the quality of text and graphics commonly found in screenshots. Additionally, PNG allows for transparent backgrounds if needed.

> [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

> [Image file type and format guide](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)

> [Choosing an image format](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format)

# Learn CSS

## Q 1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

The foreground color is like the color of the words on a page—what you see in the front. It's the main color of the text or content. The background color is like the color of the paper or canvas behind the words. It's the color that fills the space behind the text or content, making it easy to read and look nice.

## Q 2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?

1) **Choose a Theme Color:** *Pick a main color that represents the theme or mood of the blog. For example, calming blues for a travel blog or energetic reds for a fitness blog*

2) **Use Contrasting Colors:** *Ensure there is enough contrast between the background and text colors for readability. Dark text on a light background or vice versa works well*

3) **Accent Colors:** *Introduce accent colors sparingly for buttons, links, or important elements to add visual interest without overwhelming the design*

4) **Images and Graphics:** *Incorporate colorful images or graphics related to the blog's content. This not only adds vibrancy but also enhances the overall visual appeal*

5) **Consistent Color Palette:** *Stick to a consistent color palette across the website for a cohesive and professional look. This includes headings, subheadings, and other elements*

6) **White Space:** *Don't underestimate the power of white space. It not only helps with readability but also makes the colors you choose stand out*

7) **Consider Accessibility:** *Ensure that the chosen colors are accessible to a wide audience. High contrast and thoughtful color choices can improve accessibility for users with visual impairments*

## Q 3. What should you consider when choosing fonts for an HTML document?

1) **Readability:** Choose fonts that are easy to read. Avoid overly decorative or complex fonts, especially for body text.

2) **Font Size:** Ensure an appropriate font size for different elements, making text easy to read on various devices.

3) **Contrast:** Create contrast between heading and body text to guide readers through the content hierarchy.

4) **Consistency:** Maintain consistency in font choices across the website for a cohesive and professional appearance.

5) **Web Safe Fonts:** Use web-safe fonts or include web font services (like Google Fonts) to ensure consistent display across different devices and browsers.

6) **Accessibility:** Consider the readability of the chosen fonts for users with visual impairments. Aim for good contrast and legibility.

7) **Font Style:** Choose font styles (normal, italic, bold) carefully to emphasize without sacrificing readability.

8) **Hierarchy:** Establish a clear hierarchy with different fonts for headings and body text to guide users through the content.

9) **Mobile Responsiveness:** Ensure that the chosen fonts are responsive and look good on various screen sizes, especially on mobile devices.

10) **Brand Consistency:** If applicable, align the font choices with the overall brand identity to maintain consistency.

11) **Loading Speed:** Consider the impact of font files on page loading speed. Opt for efficient loading, especially for web fonts.

12) **Cross-Browser Compatibility:** Test fonts across different browsers to ensure they are displayed consistently.

## Q 4. What do `font-size`, `font-weight`, and `font-style` do to HTML text elements?

- font-size: Adjusts the size of the text.

- **font-weight: Sets the thickness or boldness of the text**

- *font-style: Defines the style of the text, such as normal or italic*

## Q 5. Describe two ways you could add spacing around the characters displayed in an `h1` element.

**Using CSS Margin:** Apply margin to the h1 element to create space around it.

> - h1 {
>  margin: 10px; /* Adjust the value as needed */
> }

**Using Letter Spacing Property:** Use the letter-spacing property to increase the space between characters.

> - h1 {
>  letter-spacing: 2px; /* Adjust the value as needed */
>}

> [Applying color to HTML elements using CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)

> [Fundamental text and font styling](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals#what_is_involved_in_styling_text_in_css)

