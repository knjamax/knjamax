# NjamasiEats Project TODO

## Database & Backend
- [x] Database schema: restaurants, categories, menu items, orders, order items
- [x] Backend API: restaurant CRUD (public list, admin manage)
- [x] Backend API: category CRUD
- [x] Backend API: menu items CRUD
- [x] Backend API: orders (create, update status, list, track)
- [x] Backend API: order items

## Frontend Infrastructure
- [x] Bilingual context provider (Swahili/English) with language toggle accessible everywhere
- [x] K.NJAMASI brand theme (colors, typography, spacing)
- [x] Global navigation with language toggle
- [x] Landing page with K.NJAMASI branding and CTA

## Customer-Facing Pages
- [x] Restaurant listing page with search and category filtering
- [x] Individual restaurant menu page with item details and quantity selectors
- [x] Shopping cart with full order summary
- [x] Checkout flow with delivery method selection (self-pickup, restaurant delivery, independent rider)
- [x] Checkout flow with payment method selection (M-Pesa, Airtel Money, Cash on Delivery)
- [x] Order confirmation page (inline in checkout with link to tracking)
- [x] Order tracking page with live status (5-second polling)

## Owner/Admin Dashboard
- [x] Dashboard layout with tabbed navigation
- [x] Restaurant management (add, edit, delete restaurants)
- [x] Menu management (add, edit, delete menu items per restaurant)
- [x] Order management (view and handle incoming orders)
- [x] Dashboard analytics/overview

## Polish & Delivery
- [x] Upload K.NJAMASI logo to web storage
- [x] Responsive design verification (mobile + desktop)
- [x] Vitest unit tests
- [x] Final checkpoint and delivery
## Restaurant Owner Registration
- [x] Database schema: restaurant_owners table for registration data
- [x] Backend API: owner registration endpoint
- [x] Frontend: Registration page with form (business name, owner name, phone, email, location, restaurant details)
- [x] Navigation: Add "Partner With Us" link visible to all users
- [x] Approval workflow: Owner registrations shown in admin dashboard for approval

## Bug Fixes
- [x] Fix landing page "How It Works" subtitle showing wrong text
