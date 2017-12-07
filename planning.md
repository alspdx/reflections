# Reflection

#### An examination of reflections, _2017_

#### by **Shane Ryan** and **Adam Smith**

## Description

| Term | Description | Implementation |
| -- |:--:| --|
| variables | Variables are names used to store information that can be called and used as a value in any key/value pair or interpolation in the Sass files. The value can be changed where the variable is declared and thus the value will change wherever the variable is called. | We use variables whenever possible to manage colors, margins, and other style values throughout the page. All of the variables are declared in one location which makes it easier to make global style changes. |
| extend | Using extend shares all of the properties from one CSS selector to another as a way to avoid repeating the same block of code, similar to using a variable. | If one selector uses the same set of properties as another existing selector, using extend allows you to call all of the properties of the selector being extended. |
| mixins | Mixins are a way to write a block of code to be reused throughout the page. Like a JavaScript function, a mixin can use a parameter to pass data to set a value in each instance the mixin is called. | We would use mixins when we need to change the same parameter(s) in multiple classes with different values. |
| functions | Sass functions are a way to repeat a block of code that accepts arguments and returns a specific value. | Functions are similar to mixins and are sometimes confused with one another, although we use functions are used where one specific value is expected to be returned. |
| nesting | Nesting is the practice of calling selectors inside another selector. This is used to affect descendants of the original parent element selected. | We use nesting to write rules for specific elements or groups of elements inside a specific container. |
| partials | Partials are files with blocks of code for a specific element, function, category, or role that will be compiled with other partials to make a complete stylesheet. | We use partials to create and organize separate files for variables, colors, layout, mixins, functions, reset/normalize, third-party libraries, and any other unique categories. |
| import | Import is a way to compile partials together. Common practice is to write a file specifically dedicated to call partials to be imported and compiled by Sass | We use an import file in each directory to compile all of the partials from that location, then import each of those files into the main Sass file to be compiled into a complete CSS stylesheet. |

## Setup

Visit the webpage [here]().

Alternately you may [Clone this repository]().
  1. Click on the link above.
  2. Click the green button marked **Clone or download**.
  3. Click **Download ZIP**.
  4. Unzip file.
  5. Open index.html in Chrome or another web browser.

## License

Copyright (c) 2017, Shane Ryan and Adam Smith

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
