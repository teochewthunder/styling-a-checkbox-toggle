# Styling a checkbox, redux: The Toggle

Once we've learned the dirty CSS trick of how to style a checkbox, we can take it a step further and render checkboxes in completely new ways. Case in point, *The Toggle*.

**HTML/CSS**
To render the toggle as follows - a rounded rectangular div (the background) in which a round div (the knob) is placed. If *on*, the background is colored dark grey and the knob i aligned right. Otherwise, the background is white and the knob is aligned left.
Also, to hide the actual checkboxes.

**JavaScript**
To set the CSS class of the above between `on` and `off`. And check/uncheck the actual checkboxes.
