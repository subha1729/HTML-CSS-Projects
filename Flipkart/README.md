# Flipkart Clone Page

A lightweight, responsive frontend clone of the Flipkart homepage built using semantic HTML5 and vanilla CSS3. This project replicates the layout, navigation bars, dropdowns, sticky components, and product grids of the e-commerce platform.

## Features

* **Two-Tier Sticky Header:** * **Top Bar:** Displays the brand identity, sub-domain toggles (Flipkart/Travel), and location preference.
    * **Search & Action Bar:** Stays fixed on scroll, containing an integrated search wrapper and interactive dropdown menus.
* **Interactive Dropdowns:** Fully CSS-driven interactive dropdown menus for the "Login" and "More" buttons.
* **Visual Category Navigation:** Horizontal category strip utilizing FontAwesome icons with custom hover transitions.
* **Promo Banner Grid:** A dynamic 3-column banner section featuring smooth transform animations (`translateY` and custom cubic-bezier shadow lifting) upon hover.
* **Responsive Product Carousels:** Flexbox-powered product deal cards housed within dedicated stylized containers ("Top Deals on Accessories" and "Top Deals on Personal Care").

## Tech Stack

* **HTML5:** Structured semantic markup.
* **CSS3:** Custom layout styles using Flexbox, CSS variables, transitions, and pseudo-classes.
* **Fonts:** Inter via Google Fonts.
* **Icons:** FontAwesome v6.4.0 (CDN Delivery).

## Project Structure

```text
├── index.html        # Main HTML structure
├── flipkart.css      # Custom stylesheet containing layout rules
└── README.md         # Project documentation

```

## Getting Started

### Prerequisites

You only need a modern web browser installed on your machine (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari).

### Running the Project Locally

1. Clone the repository to your local machine:
```bash
git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)

```


2. Navigate into the project folder:
```bash
cd YOUR_REPOSITORY_NAME

```


3. Open `index.html` directly in your browser or run it using an extension like **Live Server** in VS Code.

## Key CSS Layout Implementations

* **Sticky Behavior:** `.top` container utilizes `position: sticky` to keep navigation links seamlessly accessible while scrolling through products.
* **Hover Elevation effects:** The `.card` and `.con_box` classes utilize hardware-accelerated transforms to scale or translate upward seamlessly on mouse entry:
```css
transform: translateY(-8px);

```


* **Flexible Widths:** Product slots and banner sections adapt to various screen viewports dynamically using calculation rules (`calc()`).

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute to responsiveness tweaks or JavaScript integration.

## License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

```

```
