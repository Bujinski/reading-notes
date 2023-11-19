# HTML Lists, Control Flow with JS, and the CSS Box Model

# Learn HTML: 

## Q 1. When should you use an `unordered list` in your HTML document?

Use an unordered list (`<ul>`) in HTML when the order of items is not significant, and you want to present a list without a specific sequence or hierarchy.

## Q 2. How do you change the `bullet style` of unordered list items?

To change the bullet style of unordered list items in HTML, use the CSS property `list-style-type` and set it to the desired style (e.g., `circle`, `square`, `disc`).

## Q 3. When should you use an `ordered list` vs an `unorder list` in your HTML document?

Use an ordered list (`<ol>`) in HTML when the sequence or order of items is important. Use an unordered list (`<ul>`) when the order is not significant, and you want to present items without a specific sequence.

## Q 4. Describe two ways you can change the numbers on `list items` provided by an `ordered list`?

- 1. Use the CSS property `list-style-type` and set it to a desired style (e.g., `decimal`, `lower-roman`, `upper-alpha`).

- 2. Use the HTML attribute `start` on the `<ol>` element to specify a starting number for the list.

> [Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

> [<ol>: The Ordered List element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

> [<ul>: The Unordered List element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

# Learn CSS:

## Q 1. Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?

In the kingdom of "The Box Model," Margin is the character providing outer space between elements, preventing conflicts. Padding is the warm character ensuring cozy interiors for content within elements. Together, they maintain harmony in layout, with Margin influencing overall spacing and Padding enhancing internal content spacing for a delightful experience in the realm of HTML.

## Q 2. List and describe the four parts of an HTML elements box as referred to by the `box model`.

1. `Content`: The actual content of the element, such as text, images, or other media.

2. `Padding`: The transparent space around the content, inside the element's border. It provides cushioning between the content and the border.

3. `Border`: A visible boundary around the padding. It separates the padding from the margin and defines the outer edge of the element.

4. `Margin`: The transparent space outside the element's border. It creates space between the element and its neighboring elements, preventing them from visually blending together.

> [The box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

# Learn JS:

## Q 1. What `data types` can you store inside of an `Array`?

1. Numbers (integers, floats)

2. Strings

3. Booleans

4. Objects

5. Other arrays (nested arrays)

6. Null

7. Undefined

8. Mixed types (a combination of the above)

## Q 2. Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?

Yes, people is a valid JavaScript array. To access the values stored, you can use indices for both the outer and inner arrays:

> console.log(people[0][0]); // Outputs: pete
console.log(people[1][2]); // Outputs: accountant
console.log(people[2][3]); // Outputs: null

## Q 3. List `five` shorthand operators for assignment in javascript and describe what they do.

1. +=: Adds the right operand to the left operand and assigns the result to the left operand. For example: x += 5; is shorthand for x = x + 5;.

2. -=: Subtracts the right operand from the left operand and assigns the result to the left operand. For example: x -= 3; is shorthand for x = x - 3;.

3. *=: Multiplies the left operand by the right operand and assigns the result to the left operand. For example: x *= 2; is shorthand for x = x * 2;.

4. /=: Divides the left operand by the right operand and assigns the result to the left operand. For example: x /= 4; is shorthand for x = x / 4;.

5. %=: Computes the modulus of the left operand divided by the right operand and assigns the result to the left operand. For example: x %= 3; is shorthand for x = x % 3;.

## Q 4. Read the code below and evaluate the last `expression` and explain what the result would be and why.

The last expression (a + c) + b; would result in the string concatenation of the sum of a and the boolean c with the string b.

1. (a + c) evaluates to 10 + false, and in JavaScript, false is treated as 0 in numeric contexts. So, (a + c) results in 10 + 0, which is 10.

2. Then, the expression becomes 10 + b, where b is the string 'dog'.

3. Finally, the result is the string concatenation of 10 and 'dog', which is '10dog'.

## Q 5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

let isLoggedIn = false;

if (isLoggedIn) {
  console.log('Welcome, user!');
} else {
  console.log('Please log in to access the content.');
}

## Q 6. Give an example of when a `Loop` is useful in JavaScript.

const numbers = [1, 2, 3, 4, 5];

for (let i = 0; i < numbers.length; i++) {
  console.log(numbers[i]);
}

> [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)

> [Expressions and operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

> [Making decisions in your code — conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

> [Looping code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)
