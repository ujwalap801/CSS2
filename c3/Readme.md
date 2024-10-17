# CSS Positions

### Bydefault position of every element is static.When position is static we can't change their position by top, left right, bottom



## 1.Static
### Definition: The default positioning for all elements. The element appears in the normal document flow.
### Behavior:The element is not affected by top, bottom, left, or right properties.


## 2. Relative
## Definition: Positions the element relative to its normal position in the document flow.
## Behavior: You can use top, bottom, left, and right to move the element relative to where it would normally appear.



## 3. Absolute
## Definition: Positions the element relative to its closest positioned ancestor (an ancestor with position other than static), or the viewport if no such ancestor exists.
## Behavior:The element is removed from the normal document flow and is positioned using top, bottom, left, and right.

## 4.Fixed
## Definition: Positions the element relative to the browser window or viewport.
## Behavior:The element is removed from the document flow and remains fixed in position even when scrolling the page.


## 5. Sticky
## Definition: A hybrid between relative and fixed positioning.
## Behavior:The element is treated as relative until it crosses a specified threshold (top, bottom, left, right), at which point it becomes fixed relative to the viewport.