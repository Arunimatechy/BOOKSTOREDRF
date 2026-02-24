
# 📚 BOOKSTOREDRF

A simple **Bookstore API** built with **Django** and **Django REST Framework (DRF)** to manage books, authors, and categories.

---

## 🛠️ Tech Stack

- **Backend:** Django (core)  
- **API:** Django REST Framework  
- **Database:** SQLite (default)  
- **Language:** Python 3.x  
- **Authentication:** DRF default authentication  

---

## 🚀 Features

- Create, read, update, and delete books  
- Manage authors and categories  
- Filter and search books by title, author, or category  
- RESTful API endpoints with JSON responses  

---

## 📂 Project Structure

```

BOOKSTOREDRF/
│
├── drf/                     # Django project folder
│   ├── settings.py          # Project settings
│   ├── urls.py              # Project URLs
│   └── wsgi.py              # WSGI configuration
│
├── books/                   # App for Bookstore
│   ├── models.py            # Models for Books, Authors, Categories
│   ├── serializers.py       # DRF serializers
│   ├── views.py             # API views
│   └── urls.py              # App URLs
│
├── manage.py
└── requirements.txt

````

---

## ⚡ Installation

1. **Clone the repository**

```bash
git clone https://github.com/Arunimatechy/BOOKSTOREDRF.git
cd BOOKSTOREDRF/drf
````

2. **Create a virtual environment and activate it**

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python -m venv venv
source venv/bin/activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Apply migrations**

```bash
python manage.py migrate
```

5. **Run the development server**

```bash
python manage.py runserver
```

The API will be accessible at `http://127.0.0.1:8000/`.

---

## 📌 API Endpoints

| Method | Endpoint           | Description              |
| ------ | ------------------ | ------------------------ |
| GET    | `/api/books/`      | List all books           |
| POST   | `/api/books/`      | Create a new book        |
| GET    | `/api/books/{id}/` | Retrieve a specific book |
| PUT    | `/api/books/{id}/` | Update a specific book   |
| DELETE | `/api/books/{id}/` | Delete a specific book   |
| GET    | `/api/authors/`    | List all authors         |
| GET    | `/api/categories/` | List all categories      |

*(Replace `{id}` with the book's ID)*

---

## ✅ Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your message"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📖 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 Author

**Arunima Techy**

* GitHub: [Arunimatechy](https://github.com/Arunimatechy)
* LinkedIn: [Your LinkedIn](https://www.linkedin.com/in/your-linkedin)

```

---

