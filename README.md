# POS Sample Project (Express.js & React)

A basic Proof-of-Concept (PoC) demonstrating item management (image, name, price, description) for a POS system.

## Tech Stack
* **Frontend:** React (JavaScript)
* **Backend:** Express.js (Node.js)
* **Database:** PostgreSQL
* **File Uploads:** Multer (Express middleware)

## Features
* Add new item with image, title, price, and description.
* Display item listings with images.
* Express API endpoints handling `multipart/form-data`.

## Setup & Running
1. Clone the repository.
2. Install dependencies in both `client` and `server` directories (`npm install`).
3. Set up your PostgreSQL database connection in `server/.env`.
4. Run backend: `npm run dev` (in `/server`).
5. Run frontend: `npm start` (in `/client`).
