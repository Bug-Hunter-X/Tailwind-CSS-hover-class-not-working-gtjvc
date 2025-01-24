# Tailwind CSS Hover Class Issue

This repository demonstrates a problem where Tailwind CSS hover classes don't seem to be applied correctly.  A simple div with background colors set using Tailwind classes does not change color on hover, as expected.

## Problem
The `hover:bg-blue-700` class is not changing the background color of the div element when the mouse hovers over it.  The initial `bg-red-500` is applied, but the hover state is ignored.

## Solution
The solution involves verifying the proper inclusion of Tailwind directives in your CSS file and ensuring no conflicting styles override the Tailwind classes. It also shows the importance of checking the order of classes and ensuring that the Tailwind directives are correctly configured in your build process, such as using `@tailwind base; @tailwind components; @tailwind utilities;` in your CSS file.