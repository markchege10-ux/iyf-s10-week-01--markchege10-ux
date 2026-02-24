# Accessibility Audit report

## Issues found
* **Images** Three images were missing `alt` text
* **Forms** The message text area did not have a linked label
* **contrast** The footer text color was too light aganist the background

## How I fixed them
* Added a descriptive `alt` attributes to all `<img>` tags
* Added a `<label>` element with a `for` attribute matching the textarea`id`
## Final lighthouse accessibility score
**90/100**
