# React Props: Pokedex App
This exercise lets you practice using React components and properties

#### Create a Pokemon application (an index listing of Pokemon, a pokedex) that displays an interface that looks like this:
> ![](http://curric.rithmschool.com/springboard/exercises/react-props-pokedex/_images/pokedex.png)





#### To create the pokedex, you should use 3 components:
- #### App
    This should just render a single Pokedex component.
    (It’s common for the top-level app to not have direct logic in it, but to render the top application object — this becomes useful when you build sites that compose several different parts together.)

- #### Pokedex
    Is provided, via props, an array of objects describing different pokemon, and renders a sequence of Pokecard components using map().

- #### Pokecard
    Shows a single Pokemon, with their name, image, and type..

#### In your App component, it should pass the following list of pokemon to the Pokedex.

```
[
  {id: 4,   name: 'Charmander', type: 'fire',     base_experience: 62},
  {id: 7,   name: 'Squirtle',   type: 'water',    base_experience: 63},
  {id: 11,  name: 'Metapod',    type: 'bug',      base_experience: 72},
  {id: 12,  name: 'Butterfree', type: 'flying',   base_experience: 178},
  {id: 25,  name: 'Pikachu',    type: 'electric', base_experience: 112},
  {id: 39,  name: 'Jigglypuff', type: 'normal',   base_experience: 95},
  {id: 94,  name: 'Gengar',     type: 'poison',   base_experience: 225},
  {id: 133, name: 'Eevee',      type: 'normal',   base_experience: 65}
]
```
> For each pokemon, their `image` source should be the url + the id of the pokemon : https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/${id}.png

#### Steps : 
- Create new React App
- in the src folder, add new folder and name it components
- in the components folder, add two new files, Pokedex.js and Pokecard.js
- The Pokecard.js will recieve its data values from Pokedex.js as props
- the Pokedex.js will receive its data values from App.js as props, and it will render the Pokecard.js component inside it.
- The App.js will render the Pokedex.js component.

### Finally :
- create a gitHub Repo and push your React app to it.
- share your Repo link with the instructor/s.
