Q 2 ]  Explain the difference between Absolute and Relative positioning.

Absolute and relative positioning are two CSS positioning properties used to control the placement and layout of elements on a web page. They have different behaviors and use cases:

Absolute Positioning:

Positioning Context: When an element is set to position: absolute;, it is positioned relative to its nearest positioned ancestor. If no ancestor has a specified position property (e.g., position: relative;), the element is positioned relative to the initial containing block, which is typically the viewport.

Layout Impact: Elements with absolute positioning are removed from the normal document flow. This means they don't take up space or affect the layout of other elements. Other elements act as if the absolutely positioned element doesn't exist, which can lead to overlapping content.

Placement: You can use properties like top, right, bottom, and left to precisely control the position of the element within its positioning context. These values are usually specified in pixels or percentages.

Use Cases: Absolute positioning is commonly used for elements like tooltips, pop-up menus, or elements that need to be precisely positioned on a page.
Positioning Context: When an element is set to position: relative;, it is positioned relative to its normal position in the document flow. It retains its space in the layout, and other elements are aware of its presence.

Layout Impact: Elements with relative positioning do not disrupt the flow of other elements. They still occupy space and affect the layout, but you can adjust their position relative to their default position using properties like top, right, bottom, and left.

Placement: You can use the same positioning properties (top, right, bottom, and left) to shift the element from its default position.

Use Cases: Relative positioning is often used when you want to make minor adjustments to the position of elements within their normal flow. It's useful for fine-tuning the layout.
