# stripe-django

## Installation and Setup Instructions

1. Clone down this repository
2. Install packages from **requirements.txt**
3. Inside project directory run ***python manage.py runserver*** from terminal

## Result
There are mainly two API GET endpoints:
1. ***/buy/{id}*** - returns the session_id
2. ***/item/{id}*** - returns the HTML-Page

## Quick Check
A quick check can be done at https://stripe-django-production.up.railway.app
1. https://stripe-django-production.up.railway.app/buy/1 - returns the session_id of the first item.
2. https://stripe-django-production.up.railway.app/item/1 - returns the HTML-Page for the first item then you should click to that link.
