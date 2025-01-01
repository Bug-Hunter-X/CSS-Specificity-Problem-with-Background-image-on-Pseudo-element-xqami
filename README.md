# CSS Specificity Issue with Pseudo-elements and Background Images

This repository demonstrates a subtle bug related to CSS specificity when using background-images on pseudo-elements.  The issue arises from unexpected interactions between specificity rules and inheritance, potentially leading to the background-image not being displayed as expected.

## Problem Description

The provided `bug.css` file contains CSS code that attempts to apply a background-image to a `::before` pseudo-element.  Due to specificity and inheritance rules, this image may not appear as intended.

The `bugSolution.css` file provides a solution to ensure the background image renders correctly.

## Setup

1. Clone this repository.
2. Open `bug.html` (or a similar HTML file containing the necessary elements) in a web browser.
3. Observe the unexpected behavior.
4. Examine the `bugSolution.css` for a corrected implementation.

## Solution

The solution involves carefully managing CSS specificity to ensure the pseudo-element's styles override any conflicting styles.  The solution file demonstrates this approach.