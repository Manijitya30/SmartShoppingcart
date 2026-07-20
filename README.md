# SmartShoppingcart

An intelligent retail navigation and shopping assistance platform that combines real-time indoor navigation, shopping list management, smart cart synchronization, feedback analytics, and admin monitoring into one unified retail ecosystem.

---

## Live Demo

### Admin / Staff Portal

- Backend: https://smartshoppingcart.onrender.com
- Frontend: https://smart-shoppingcart.vercel.app/

### Smart Cart Portal

- Backend: https://cart-backend-rqxe.onrender.com
- Frontend: https://smartcart-frontend-topaz.vercel.app/

---

## Demo Credentials

### Staff Login

- Phone Number: `9908552005`
- Password: `staffpassword`

---

## Key Features

## Smart Cart Features

- QR-based shopping list transfer from mobile to cart
- Real-time shopping list tracking
- Graph-based indoor navigation using A* pathfinding
- Dynamic route optimization across 29+ store nodes
- Cart-to-server synchronization
- Offline-first architecture using local storage
- Customer feedback collection for unavailable products
- Real-time cart location visualization
- Personalized product recommendations and offers

## Admin Features

- Product inventory management
- Category and aisle management
- Offer and discount management
- Customer feedback monitoring
- Shopping analytics dashboard
- Route and navigation data management
- Real-time synchronization with smart carts
- Store layout and node management

---
## Tech Stack

### Frontend

- React.js
- JavaScript
- CSS

### Backend

- Node.js
- Express.js

### Databases

- MySQL
- SQLite

### Algorithms

- A* Pathfinding
- Graph-based Route Optimization
- Nearest Node Mapping

### Deployment

- Vercel
- Render

---

## Project Highlights

- Developed a distributed smart retail platform with independently deployed admin and smart cart services.
- Implemented graph-based indoor navigation across 29+ interconnected store nodes.
- Designed an offline-first synchronization engine for shopping lists, cart items, feedback, and cart location tracking.
- Built scalable REST APIs for admin, cart, inventory, feedback, navigation, and analytics modules.
- Deployed frontend applications on Vercel and backend services on Render.

---

## Modules

### Admin Portal

The admin portal allows store staff to manage products, categories, aisles, offers, feedback, analytics, store layout, and navigation nodes.

### Smart Cart Portal

The smart cart portal helps customers access their shopping list, navigate through the store, track cart items, receive recommendations, and submit feedback.

---

## Navigation System

SmartShoppingcart uses a graph-based indoor navigation model where store locations are represented as nodes and paths are represented as weighted edges.

The system uses:

- A* pathfinding for shortest-path calculation
- Nearest-node mapping for cart location detection
- Route optimization for multi-item shopping lists
- Real-time cart position updates for navigation visualization


