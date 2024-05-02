## A blog website written in Django.

This is a python web app that showcases how a business might use a website to advertise its services to potential clients. It is written using the Django web framework.<br>

When a user visits one of the pages in the website, the request url will be processed by the urls.py file in the main project directory. <br>

If the url requests for the homepage, Django will direct it to the index function in views.py. 

image



The index function takes this request as a parameter and renders the “home.html” template, which is given back to the client as the response.<br>


For the other pages, Django will parse the request and pass it on to the pages function. This function takes the string value in the url and uses it to determine which template it will render. A page that doesn’t exist within the app will trigger Django to respond with an error page.
