# Car-Management-Application

# Tech Stack
Backend:
Framework: Django (Python) with Django REST Framework (DRF)
Database: PostgreSQL (Relational DB for structured data)
Authentication: JSON Web Tokens (JWT)
Image Storage: AWS S3 / Cloudinary / Local Filesystem
API Documentation: Swagger via drf-yasg
Frontend:
Framework: React (popular for frontend applications)
UI Framework: Material UI or Tailwind CSS
HTTP Library: Axios (for making API calls)
Deployment:
Backend: Deploy on Heroku/AWS/GCP
Frontend: Deploy on Vercel/Netlify
Frontend
1. Pages
Login/Signup:

Use a simple form for authentication.
Integrate backend API for JWT-based login/signup.
Dashboard:

Display a list of cars belonging to the logged-in user.
Include a search bar for filtering.
Car Creation:

Form to upload up to 10 images and set car details.
Car Detail:

Display car details with options to edit/delete.
Deployment
Backend:

Use Heroku for deployment.
Set up PostgreSQL using Heroku addons.
Frontend:

Deploy using Vercel.
Configure the backend API URL in the frontend.
API Documentation:

Use Swagger UI or Postman documentation to expose /api/docs.
