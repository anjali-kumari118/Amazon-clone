# Amazon Clone

A frontend clone of Amazon's homepage built with HTML, CSS, and responsive design. This project demonstrates modern web design principles with a Flask backend for local development and serving.

## 📋 Project Overview

This is a static Amazon homepage clone featuring:
- **Responsive Navigation Bar** - Logo, delivery location, search bar, account menu, and shopping cart
- **Hero Section** - Featured promotional banner
- **Product Categories Grid** - 8 product category cards with images for browsing
- **Footer Section** - Quick links and company information
- **Font Awesome Icons** - Modern iconography throughout the interface

## ✨ Features

- Clean, responsive HTML structure
- Professional CSS styling mimicking Amazon's design
- Product category showcase with background images
- Interactive hover effects on navbar elements
- Search bar with category dropdown
- Shopping cart interface
- Footer with multiple link categories
- Cross-browser compatible

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3
- **Icons**: Font Awesome 6.7.2
- **Backend Framework**: Flask (for local development)
- **Python Version**: 3.x

## 📦 Prerequisites

- Python 3.7 or higher
- pip (Python package manager)
- Git (optional, for cloning the repository)

## 🚀 Installation

### Step 1: Clone or Download the Project
```bash
# If using git
git clone <repository-url>
cd Amazon-clone

# Or download and extract the ZIP file
```

### Step 2: Create a Virtual Environment
```bash
# On Windows
python -m venv venv

# On macOS/Linux
python3 -m venv venv
```

### Step 3: Activate the Virtual Environment
```bash
# On Windows (PowerShell)
.\venv\Scripts\Activate.ps1

# On Windows (Command Prompt)
venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate
```

### Step 4: Install Dependencies
```bash
pip install -r requirements.txt
```

## 💻 Running the Project

### Option 1: Using Flask (Recommended)
```bash
# Make sure virtual environment is activated
flask run
```

Then open your browser and navigate to:
```
http://localhost:5000
```

### Option 2: Open Directly in Browser
Simply open the `index.html` file in your web browser:
- Windows: Right-click on `index.html` → Open with → Your browser
- macOS: Double-click `index.html` or drag it to your browser
- Linux: Right-click → Open with → Your browser

## 📁 Project Structure

```
Amazon-clone/
├── index.html              # Main HTML file
├── index.css               # Stylesheet
├── requirements.txt        # Python dependencies
├── README.md               # This file
├── venv/                   # Virtual environment (auto-created)
├── Amazon-Logo (1).jpg     # Amazon logo image
├── amazon-logo.jpg         # Alternative logo
├── box1.jpg to box8.jpg    # Product category images
└── front.jpg               # Hero section banner image
```

## 📋 Required Dependencies

The project uses the following Python packages (in `requirements.txt`):

- **Flask 3.0.0** - Web framework for serving the application
- **Flask-CORS 4.0.0** - Handle cross-origin requests
- **python-dotenv 1.0.0** - Environment variable management
- **Werkzeug 3.0.1** - WSGI utilities
- **requests 2.31.0** - HTTP client library
- **Jinja2 3.1.2** - Template engine

## 🎨 Customization

To customize the project:

1. **Change Images**: Replace the `.jpg` files in the project root with your own images
2. **Update Colors**: Modify the color values in `index.css`
3. **Edit Content**: Update text and links in `index.html`
4. **Add Functionality**: Create backend routes in a Flask app.py file

## 📝 Notes

- All images are loaded locally from the project directory
- Font Awesome icons are loaded from CDN (requires internet connection)
- The project is currently static but can be extended with Flask backend features
- Search functionality and cart features are currently frontend-only

## 🔗 Resources

- [Amazon Official Site](https://www.amazon.com)
- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Flask Documentation](https://flask.palletsprojects.com/)
- [Font Awesome Icons](https://fontawesome.com/)

## 📄 License

This is a personal learning project created for educational purposes only.

---

**Last Updated**: March 2026
