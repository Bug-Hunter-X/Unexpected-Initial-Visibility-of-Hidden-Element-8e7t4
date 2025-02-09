# Unexpected Initial Visibility of Hidden Element

This repository demonstrates an uncommon bug in HTML where an element intended to be initially hidden is not hidden on page load. The issue arises from an oversight in setting the initial display style of the element.

## Bug Description
The `div` element with the id "myDiv" is supposed to be hidden initially but appears visible upon page load. This is unexpected behavior. The `showHide()` function works correctly to toggle its visibility; however, the initial state is incorrect, leading to a visual discrepancy.

## Solution
The solution involves explicitly setting the `display` style of the `div` element to `none` in the HTML or using CSS to set the initial state to hidden.

## How to reproduce the bug
1. Open `bug.html` in a web browser.
2. Observe that the text within the `div` is visible upon page load.
3. Click the "Show/Hide" button. The text correctly hides and shows as expected.

## How to solve the bug
1. Open `solution.html` in a web browser.
2. Observe that the text within the `div` is initially hidden.
3. Click the "Show/Hide" button. The text correctly hides and shows.

