# Travel Planner – Smart Itinerary Management

## Overview
Travel Planner is a web-based application that helps users plan and manage their trips efficiently. It allows users to create itineraries, add destinations, and track travel details in an organized manner. The system is built with a Django backend and a REST API for seamless integration.

## Features
- **User-Friendly Itinerary Management** – Add and organize travel plans with ease.
- **Destination Management** – Store details of multiple travel destinations.
- **REST API Support** – Allows easy interaction with frontend and external services.

##  Technologies Used
- **Python & Django REST Framework** – Backend development.
- **SQLite** – Database for storing travel data.
- **Django Admin Panel** – Manage users and travel details.

## Project Structure
```
Travel-Planner/
│── manage.py                # Django project manager
│── travel_planner/
│   ├── settings.py          # Project settings
│   ├── urls.py              # URL routing
│   ├── wsgi.py              # WSGI configuration
│── itineraries/
│   ├── models.py            # Database models
│   ├── views.py             # API views
│   ├── serializers.py       # Data serialization
│   ├── urls.py              # Itinerary-related endpoints
```

## Getting Started
### Prerequisites
Ensure you have the following installed:
- **Python 3.x**
- **Django & Django REST Framework**

### Installation & Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/Travel-Planner.git
   cd Travel-Planner
   ```
2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run database migrations**
   ```sh
   python manage.py migrate
   ```
4. **Start the development server**
   ```sh
   python manage.py runserver
   ```

## Usage
- Access the API at `http://127.0.0.1:8000/`
- Modify `itineraries/views.py` to customize API responses.
- Use Django Admin to manage travel records.

## License
This project is licensed under the MIT License.

