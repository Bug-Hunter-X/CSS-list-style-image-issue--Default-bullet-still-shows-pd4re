# CSS list-style-image Issue: Default bullet point still shows

This repository demonstrates a common issue when using the `list-style-image` property in CSS.  The problem arises when you try to replace the default bullet point with a custom image without first setting `list-style-type` to `none`. 

The `bug.css` file shows the problematic code. The solution is provided in `solution.css` which properly removes the default bullet and displays the image only.

## How to Reproduce
1. Open `bug.html` in your browser.
2. Observe that the image appears alongside the default bullet point.
3. Open `solution.html` in your browser.
4. Notice the image correctly replaces the default bullet.