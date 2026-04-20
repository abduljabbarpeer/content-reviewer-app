# Subjective
The "Product Showcase" Component
The Objective
Design and build a responsive card-based layout that adapts its structure based on the device screen size. This project will test your mastery of the CSS Box Model, positioning strategies, and the "Mobile First" design philosophy.

1. Structural Requirements (HTML)
Container: A main <section> or <div> to wrap all cards.
Cards: At least three <article> elements representing "Service Cards."
Content: Each card must contain an image (or a placeholder div), an <h3> title, and a short description.
The Action Button: A "Support" or "Help" button located outside the main content flow.
2. Styling & Layout Requirements (CSS)
A. The Box Model & Sizing
The Global Reset: Apply box-sizing: border-box to all elements.
Note: This is critical to ensure that padding and borders do not increase the physical width of your cards, preventing layout "breaks."

Card Styling: * Set a specific Padding (inner space for text).
Apply a Border (1px solid) and a slight border-radius.
Use Margin to ensure cards do not touch each other.
B. Responsive Breakpoints (Media Queries)
You must use a Mobile-First approach (write mobile styles first, then use @media for larger screens).

Device Type	Breakpoint	Layout Requirement
Mobile	Default	Stacked: Cards take up 100% width and sit vertically.
Tablet	min-width: 600px	Two-Columns: Use display: flex or grid to show two cards per row.
Desktop	min-width: 1024px	Max-Width: The container must not exceed 1200px and must be centered on the screen using margin: auto.
C. Positioning
Fixed Action Button: Create a button that stays "stuck" in the bottom-right corner of the screen, regardless of how much the user scrolls.
Property: Use position: fixed with appropriate bottom and right values.