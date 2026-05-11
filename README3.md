# Ecommerce Frontend Design - Internship Project

A responsive ecommerce website built with HTML5, CSS3, and vanilla JavaScript based on a Figma design. Inspired by Alibaba B2B platform layout.

## Pages

The project includes four pages combined into a single HTML file with smooth client-side navigation:

1. **Home Page** - Landing page with hero banner, deals, product categories, recommendations, supplier inquiry form, and regions.
2. **Product Listing Page** - Filterable grid of products with sidebar filters and pagination.
3. **Product Details Page** - Single product view with image gallery, supplier info, size dropdown, quantity selector, Add to Cart button, customer reviews, and related products.
4. **Cart Page** - Shopping cart with items, coupon section, order summary, checkout, and saved-for-later products.

## Features

### Home Page
- Hero section with sidebar categories and trending banner
- Deals and offers with countdown timer
- Home & Outdoor and Consumer Electronics product showcases
- "Send requests to suppliers" inquiry banner with form
- Recommended items grid
- Extra services section
- Suppliers by region

### Product Listing Page
- Comprehensive sidebar filters (Category, Brands, Features, Price range, Condition, Ratings)
- Grid view (default) and List view toggle
- Product cards with image, title, price, rating, reviews, "Buy Now" button
- Pagination

### Product Details Page (Week 3)
- Main image with 6 clickable thumbnails
- Tiered pricing (50-100, 100-700, 700+ pcs)
- Size dropdown (S, M, L, XL, XXL)
- Quantity selector with +/- buttons
- Add to Cart button with toast notification
- Supplier card with verified badge
- Tabbed sections (Description / Reviews / Shipping / About seller)
- Customer Reviews with rating breakdown bars
- Specifications table and feature checklist
- "You may like" sidebar
- Related products grid

### Cart Page (Week 3)
- Cart items with details, quantity dropdown, remove/save actions
- Coupon code section
- Order summary (Subtotal, Discount, Tax, Total)
- Checkout button with payment method icons
- Service info row (Secure payment, Customer support, Free delivery)
- Saved for later section

## Interactivity (Week 3 JavaScript)

- Page navigation without reloading
- Add to Cart with cart counter badge
- Toast notifications for user actions
- Quantity +/- selector
- Size dropdown integration
- Search bar with suggestions dropdown (focus to open)
- Tab switching on Details page
- Thumbnail image gallery
- Grid/List view toggle
- Cart item remove with fade animation
- Coupon apply feedback
- Move to cart from saved items

## Technologies

- **HTML5** — Semantic structure
- **CSS3** — Flexbox, Grid, transitions, responsive media queries
- **Vanilla JavaScript** — All interactivity
- **Font Awesome** — Icons
- **Google Fonts (Inter)** — Typography

## Project Structure

```
ecommerce-website/
├── index.html       # All four pages combined
├── css/
│   └── style.css    # All styles with section comments
├── images/
└── README.md
```

## How to Run

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Internet connection required for icons and product images

## Browser Compatibility

Tested on Chrome, Firefox, Edge, and Safari (latest versions).

## Responsive Design

- Desktop (1024px+): Full layout
- Tablet (768-1024px): Adjusted columns
- Mobile (<640px): Single column

## Author

Levi - Software Quality Engineering Student

## Project Status

- Week 1: Header & Footer ✓
- Week 2: Home page & Product listing page ✓
- Week 3: Product details page & Interactivity ✓
