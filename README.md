# Ecommerce-Site
A simple ecommerce site in which backend is created with Django and frontend is created with Vue.js.
You can select the products, add them to the cart and complete the transaction.
Stripe's API is integrated to authorise your card and complete the required transaction.

## Features!

  - One can also add products from the admin portal.
  - User can then run the server, create an account, login and select the products.
  - One can also filter products, using various categories.
  - After selecting the products, user can checkout and complete the transaction with the card.

## Requirements

* [Python 3+](https://www.python.org/download/releases/3.0/?) - Python 3.6+ verion
* [Django](https://www.djangoproject.com/) - Django for backend
* [Django REST Framework](https://www.django-rest-framework.org/) - Django REST Framework for designing REST APIs


## Steps to Run
1. Go to EcomSite_django folder.
2. Install Django:
   ```sh
   $ python -m pip install django
   ```
3. Install Django Rest Framework:
   ```sh
   $ pip install djangorestframework
   ```
4. Add `rest_framework` to your `INSTALLED_APPS` setting.
    ```sh
   INSTALLED_APPS = [
    ...
    'rest_framework',
   ]
   ```
5. Run the backend server with:
   ```sh
   $ python manage.py runserver
   ```
6. Install Vue.js:
   ```sh
   $ npm install vue
   ```
7. Run the frontend server with:
   ```sh
   $ npm run serve
   ```
   
## Images

#### Home Page
![Screenshot (750)](https://user-images.githubusercontent.com/39690050/163922983-bfbad32f-2d15-41fd-8dee-a82b8a3fc4a8.png)

#### Product Description
![Screenshot (752)](https://user-images.githubusercontent.com/39690050/163922773-740978fc-161a-4a63-b94e-6ec1bca8ecc4.png)

#### Cart Items
![Screenshot (751)](https://user-images.githubusercontent.com/39690050/163922908-52815b07-1d22-423a-abec-1c57e9f6825b.png)
