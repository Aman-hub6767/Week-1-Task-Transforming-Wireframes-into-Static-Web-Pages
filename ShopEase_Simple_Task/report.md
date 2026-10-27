# ShopEase E-commerce Website — Short Report

## Objective
The objective of this task was to create a static e-commerce webpage from a wireframe using HTML and CSS. The page shows an online store layout with categories, product cards, an offer banner and a footer.

## Files
- `index.html` contains the structure and text of the webpage.
- `style.css` contains the colours, spacing, layout and responsive styles.
- `report.md` explains the main design decisions and testing plan.

## Design decisions
I used a simple navy, white and light-blue colour scheme to give the website a clean shopping-store look. The page is divided into clear sections so visitors can find categories and products easily. Product cards show a product symbol, name, rating, price and a button.

I used semantic HTML elements such as `header`, `nav`, `section` and `footer`. CSS Grid is used for the category and product cards, while Flexbox is used for the navigation, hero area and offer banner. The CSS is grouped by page section to make it easier to read and edit.

## Responsive design
Media queries are included for tablet and mobile screen sizes. On smaller screens, the hero section stacks vertically and the category and product grids use fewer columns. This helps the page fit different screen widths.

## Challenges and solutions
One challenge was keeping the product cards organised on different screen sizes. I used CSS Grid and media queries to change the number of columns. Another challenge was making the hero section fit on mobile, so I changed it from a row layout to a column layout on small screens.

## Testing plan
Before submitting, I will open `index.html` in a browser and check the page at desktop, tablet and mobile widths. I will also check that the navigation links move to the correct sections and that the page does not scroll horizontally on a mobile screen.

## Conclusion
This project demonstrates the basic use of HTML for page structure and CSS for styling and responsive layouts. It is a static student project; it does not include JavaScript, a real shopping cart, payment processing or a backend.
