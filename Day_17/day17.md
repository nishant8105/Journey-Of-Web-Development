## Date 25/01/2026
## day 17 of learning web development
Today I have learn about CSS `position` Property

The `position` property in CSS is used to specify how an element is
positioned in a document. It works together with properties like `top`,
`right`, `bottom`, and `left`.


### 🔹 1. position: static (Default)

-   This is the default value.
-   Elements are positioned according to the normal document flow.
-   `top`, `right`, `bottom`, and `left` do NOT work.



### 🔹 2. position: relative

-   Positioned relative to its normal position.
-   You can move it using `top`, `right`, `bottom`, and `left`.
-   The original space is still reserved.


### 🔹 3. position: absolute

-   Positioned relative to the nearest positioned ancestor.
-   Removed from normal document flow.
-   No space is reserved.

### 🔹 4. position: fixed

-   Positioned relative to the viewport (browser window).
-   Stays fixed even when scrolling.
-   Removed from document flow.


### 🔹 5. position: sticky

-   Acts like `relative` until a scroll threshold is met.
-   Then behaves like `fixed`.
-   Commonly used for sticky headers.

### 🎯 When to Use

-   Use **relative** for small adjustments.
-   Use **absolute** for precise positioning inside a container.
-   Use **fixed** for floating buttons or navigation bars.
-   Use **sticky** for headers that stay visible while scrolling.
