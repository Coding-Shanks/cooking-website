# Culinary Hub - Advanced Cooking Website

**Culinary Hub** is a visually appealing and feature-rich cooking website that allows users to explore and filter delicious recipes by category or search terms. Built with a modern frontend and powered by a Flask backend, it offers interactive features and a smooth user experience.

## Features

- **Interactive Recipe Search**: Filter recipes dynamically via a search bar.
- **Category-Based Filtering**: Browse recipes by Breakfast, Lunch, Dinner, and Desserts.
- **Newsletter Signup**: Capture user emails with a frontend-only subscription form.
- **Modern UI**: Clean design with smooth animations, responsive layout, and intuitive navigation.
- **API Endpoint**: A JSON API served by Flask to fetch and filter recipe data.

## Technologies Used

- **Frontend**:  
  - HTML5  
  - CSS3 (Responsive design + animations)  
  - JavaScript (DOM manipulation, fetch API)  
- **Backend**:  
  - Python 3  
  - Flask  
  - JSON for recipe storage

## Project Structure

```
project-root/
├── static/
│   ├── styles.css
│   ├── script.js
│   └── recipes.json
├── templates/
│   └── index.html
├── app.py
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.x installed  
- `pip` for installing Python packages

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Coding-Shanks/culinary-hub.git
cd culinary-hub
```

2. **Create a virtual environment (optional)**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install Flask
```

4. **Run the Flask app**
```bash
python app.py
```

5. **Visit the app**

Open your browser and go to: [http://localhost:5000](http://localhost:5000)

## API Endpoint

- `GET /api/recipes?search=term`  
  - Returns filtered recipes based on the title, description, or category.  
  - If `search` is omitted, returns all recipes.

## Future Enhancements

- Add a backend for storing newsletter signups.
- Enable individual recipe pages.
- Add user authentication for saving favorite recipes.
- Use a database (e.g., SQLite or PostgreSQL) instead of JSON for scalability.

## License

This project is open-source and available under the MIT License.

**Enjoy cooking with Culinary Hub!**
