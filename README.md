**Pokedex Project**

This is a simple implementation of a Pokedex app that allows you to view a list of Pokemons.

The main focus for review should be the server side code in `pokedex/pokedex_app/views.py`, and the client side code in `pokedex/pokedex_app/templates/pokedex.html`.

The code implements a caching mechanism that stores the pokemons data in cache for TTL time configured to improve performance. If the cache is invalidated, the data is retrieved from the database again.

##### Getting Started
###### Prerequisites
`Python 3.x , Django 3.x `
###### Installing

Clone the repository
https://github.com/baruchgans/Pok-dex


Install the dependencies: 
`pip install -r requirements.txt
`

Run the development server:
`python manage.py runserver 
`

Open your web browser and navigate to http://127.0.0.1:8000/pokedex_app/ 
You should see the list of Pokemons.

Create and activate a virtual environment: 
`python -m venv venv `
`source venv/bin/activate`
