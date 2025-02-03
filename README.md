# CSS Absolute Positioning Without Offsets

This repository demonstrates a common CSS issue related to using `position: absolute;` without specifying the offset properties (`top`, `right`, `bottom`, `left`).  The `bug.css` file contains the problematic code, while `bugSolution.css` provides the corrected version.

**Bug:** The element with `position: absolute;` fails to render correctly because its position is not defined relative to its parent container.

**Solution:** Setting at least one of the offset properties (`top`, `right`, `bottom`, `left`) resolves the issue by specifying the element's position within its parent.