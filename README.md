Here is the translation of your API documentation into English:

🎬 Movie Review and Favorites List API
This project is a RESTful API developed using the Flask framework. Users can register, log in, review movies, add movies to their favorites, and manage their profiles.

🚀 Features
✅ User registration and login (JWT-based authentication)

👤 Profile viewing and updating

🔒 Password changing

🎥 Movie listing, searching, and detail viewing

📝 Adding, editing, and listing reviews

⭐ Adding, listing, and removing favorite movies

📚 Listing categories

🔐 CORS and bcrypt encryption support

🛑 Global error handling

📡 API Endpoints
🧑 User Operations
POST /api/users/register → User registration

POST /api/users/login → Login

GET /api/users/me → Get user info (JWT required)

PUT /api/users/profile → Update profile (JWT required)

PUT /api/users/password → Change password (JWT required)

🎞️ Movies
GET /api/movies → List all movies

GET /api/movies/<movie_id> → Movie details and reviews

GET /api/movies/search?q=<query> → Search by movie name

📝 Reviews
POST /api/reviews → Add review (JWT required)

PUT /api/reviews/<review_id> → Update review (JWT required)

GET /api/reviews → List all reviews

⭐ Favorites
POST /api/favorites → Add to favorites (JWT required)

GET /api/favorites → Get favorites (JWT required)

DELETE /api/favorites/<favorite_id> → Remove from favorites (JWT required)

📚 Categories
GET /api/categories → Get all categories
