## venv — Creation of virtual environments
    ### Create a virtual environment
    python -m venv venv

    ### Activate the virtual environment (Linux/macOS)
    source venv/bin/activate

    ### Activate the virtual environment (Windows)
    venv\Scripts\activate


python manage.py makemigrations
python manage.py migrate

python manage.py runserver
curl http://127.0.0.1:8000/api/books/

Request Body:
```{
  "title": "The Great Gatsby",
  "author": "F. Scott Fitzgerald",
  "published_date": "1925-04-10"
}```

