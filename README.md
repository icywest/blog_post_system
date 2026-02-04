# Blog Post System
A simple social media–style web application, focused on creating and viewing posts.

This project was built as a proof of concept to demonstrate the full Node.js application flow, including controllers, middleware, routes, sessions, and server-side rendering. The goal is to validate structure and process rather than build a production-ready platform.

---

## Features
- Create and view posts
- Commenting system
- JSON-based data persistence
- Session handling with Express Sessions
- MVC-inspired structure (controllers, routes, middleware, models)
- Server-side rendering with Handlebars
- Responsive layout

---

## Tech Stack

### Backend
- Node.js / Express.js

### Frontend
- Handlebars (HBS)
- CSS (responsive design)

### Data Storage
- JSON files (no database)

---

## Setup & Installation

1. Clone the repository

   ```bash
   git clone https://github.com/icywest/blog_post_system.git
   cd blog_post_system
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Environment configuration
   Create a `.env` file in the root directory and add the following variables:

   ```env
   PORT=3000
   SESSION_SECRET=your_secret_key
   ```

4. Run the application

   ```bash
   npm start
   ```

5. Open in browser

   ```txt
   http://localhost:3000
   ```

---

## Notes

* This project uses JSON files instead of a database
* Designed for learning and architectural demonstration
* Not intended for production use