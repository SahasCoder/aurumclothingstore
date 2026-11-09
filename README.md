# AURUM CLOTHING — Premium Frontend

A mobile-first editorial fashion storefront for GitHub Pages. Built as a static, no-build website so the frontend can be previewed and refined before the backend is introduced.

## Storefront experience
- Premium campaign-led homepage with locally optimized editorial photography.
- Responsive desktop navigation, search and mobile search field.
- Product search with live suggestions.
- Category discovery and category filters.
- Product catalogue with sorting, size and maximum-price filters.
- Product cards with wishlist controls and product-detail entry points.
- Dedicated, shareable full-page product routes using #product/product-id.
- Product details with size selection, quantity controls, image zoom, fit notes and related products.
- Recently viewed products.
- Local demo shopping bag with quantity editing and subtotal.
- Local wishlist, saved between visits on the same browser.
- Mobile bottom navigation, touch-friendly controls, drawers and full-screen filter panel.
- Reduced-motion support and lazy-loaded product images.

## Current frontend-only behavior
The catalogue contains 10 sample products and demo prices. Cart and wishlist data are stored in browser localStorage. Adding an item to the bag is a frontend interaction only.

The following are intentionally not active yet:
- Live product inventory and per-size stock
- Customer accounts and authentication
- Checkout and order creation
- Payment gateway integration
- Delivery partner integration, pincode serviceability and tracking
- Admin dashboard and product management
- Real reviews, ratings, coupons and promotions

No real payment is collected and no order is placed by this preview. Store policy, delivery promises and stock information must be confirmed before launch.

## Project structure
- index.html — complete static storefront
- assets/ — original AURUM brand/product images and optimized editorial assets
- ASSET-CREDITS.md — external photography source credits

## Deploy
GitHub Pages publishes the main branch root. No npm install or build step is required.

## Next phase
The frontend is structured so the embedded demo product catalogue and local cart/wishlist can later be replaced with API-backed product, inventory, account, cart, checkout, payment, shipping and admin services.
