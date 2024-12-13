# CSS Filter Blur on Fixed Position Element Bug

This repository demonstrates a subtle bug related to applying the CSS `filter: blur()` property to an element with `position: fixed`.  When blurring a fixed element, the blur radius can extend beyond the element's boundaries, unexpectedly affecting other page elements.

## The Problem

The `bug.css` file contains the problematic CSS.  The blur radius is large enough to cause noticeable blur on elements outside the intended area.

## The Solution

The `solution.css` file shows a corrected approach to mitigate the issue. By using a wrapper element with the blur, the issue is resolved. 