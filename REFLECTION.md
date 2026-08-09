# Reflection
**Student Name:** Andrea Aston
**Student ID:** BECE/21/SS/002
**Date:** 9th August, 2026

7. I used box-sizing: border-box with the * selector because it makes layout sizing much easier to predict. With border-box, the declared width already includes the padding and border, so if an element has width: 200px and padding: 20px on both sides, the actual rendered width stays 200px. Without border-box, the width only applies to the content area, so the total rendered width becomes 200px + 20px + 20px = 240px, which is larger than expected.

8. I used position: absolute on the badge inside a position: relative card because the badge should be positioned relative to the card itself. If I remove position: relative from the card, the badge will no longer be anchored to the card and will instead be placed relative to the next positioned ancestor or, if there is none, the page itself. That means the badge could appear in the wrong place and no longer stay attached to the card.

9. If I have h2 { color: red }, .title { color: blue }, and h2.title { color: green }, then an h2 element with the class title will be green. The reason is specificity: h2 has specificity 0,0,1; .title has 0,1,0; and h2.title has 0,1,1. Since h2.title has the highest value in the class column and is more specific than either of the other selectors, its rule wins.

10. In real web design, static positioning is the normal flow used by a paragraph of text in a news article on BBC News. Relative positioning is useful for a small element such as a button on a product page that needs to be nudged slightly without affecting the layout around it. Absolute positioning is commonly used for a notification badge on a shopping cart icon in Amazon or a similar e-commerce app. Fixed positioning is used for a persistent menu bar or a back-to-top button that stays visible while scrolling. Sticky positioning is used for a navigation bar or table of contents that remains at the top of the screen once the user scrolls past it, such as the top menu on GitHub or the sticky section navigation on Medium.

