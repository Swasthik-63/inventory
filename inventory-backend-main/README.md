
# Inventory Management Backend (Activity 2)

## Tech Stack
- Node.js
- Express.js
- MongoDB (local)
- Mongoose

## Setup Instructions

1. Clone the repo:
```bash
git clone <repo-url>
cd inventory-backend
```

2. Install dependencies:
```bash
npm install
```

3. Create `.env` file:
```
PORT=5000
MONGO_URI=mongodb://localhost:27017/inventory
```

4. Run the app:
```bash
npm run dev
```

## API Endpoints

- `POST /api/products` – Create a product
- `GET /api/products` – Get all products
- `GET /api/products/:id` – Get a product by ID
- `PUT /api/products/:id` – Update a product
- `DELETE /api/products/:id` – Delete a product
