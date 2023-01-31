**Pokedex Project**

This is a simple implementation of a Pokedex app that allows you to view a list of Pokemons.

###### Main Focus for Review
When reviewing the code, please focus on the following two main files:

`pokedex/pokedex_app/views.py` for the server-side code
`pokedex/pokedex_app/templates/pokedex.html` for the client-side code

###### Caching Mechanism
The app has implemented a caching mechanism that stores the Pokemons data in cache for a configurable amount of time (TTL). This is done to improve the performance of the app and avoid unnecessary calls to the database. If the cache is invalidated, the data is retrieved from the database again.

##### Getting Started
###### Prerequisites
`Python 3.x , Django 3.x `
###### Installing

Clone the repository
`git clone https://github.com/baruchgans/Pok-dex.git`



Install the dependencies: 
`pip install -r requirements.txt
`

Run the development server:
`python manage.py runserver 
`

Once you have completed these steps,
you can open your web browser and navigate to http://127.0.0.1:8000/pokedex_app/ to see the list of Pokemons.


