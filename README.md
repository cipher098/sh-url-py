## Django URL Shortener
A simple URL shortner made with love using Django.

**Tools:**

 - Django
 - Django Rest Framework
 - Ajax

**Demo:** [https://sh-url-py.herokuapp.com/](https://sh-url-py.herokuapp.com/)

**API:**
URL: `https://sh-url-py.herokuapp.com/api/shorten-url/`
Method: `POST`
Body:

```json
{
"url": "https://www.google.com/"
}
```

**Run:**

 - Clone the project
 - Do `cd <project-folder>` and `pip install requirements.txt` 
 - Run `python manage.py makemigrations` and `python manage.py migrate`
 - Deploy test server: `python manage.py runserver` 
