# Uncommon HTML Bug: Unexpected innerHTML behavior

This repository demonstrates an uncommon bug related to the use of `innerHTML` in HTML. The bug arises from an incorrect approach to appending content to an existing div element using `innerHTML`.

## Bug Description
The primary issue lies in the way `innerHTML` is used to modify the content of a div.  Instead of appending new content, the existing content is unintentionally overwritten.

## Bug Solution
The solution involves using appropriate methods for modifying the DOM to append content without overwriting it. This can be achieved by using `insertAdjacentHTML`. 
