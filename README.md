# Pokedex

POC app using [pokeapi](https://pokeapi.co/docs/v2) to showcase good practices and clean 
architecture in android

## Table of contents

* [Requisites](#requisites)
* [Analysis](#analysis)
* [Architecture](#architecture)
* [Technologies](#technologies)
* [Credits](#credits)
* [License](#license)

## Requisites

### User Stories

1. As user, when I launch the app I want to see the full list of existing pokemon so I can scroll
   through it.
2. As user, when I launch the app, if I have no connectivity, I want to see the last downloaded
   list, so I can scroll through it.
3. As user, I want the list entries to contain the species name and the picture of each pokemon.
4. As user, I want to be able to search for a specific pokemon by entering all or part of its
   species name.
5. As user, when I tap on one of the pokemon list entries, I want to see more information of that
   pokemon.
6. As user, when I see the information of a pokemon, I want to be able to catch it.
7. As user, when I catch a pokemon, I want to be given the option to give it a nickname.
8. As user, I want to be able to see the list of pokemon I've caught, so I can scroll through it.
9. As user, I want the list of my captured pokemon to use the nickname instead of the species name.
10. As user, I want to be able to search for a specific pokemon by entering all or part of its
    nickname (or species name, if no nickname was chosen).
11. As user, I want to be able to order my captured pokemon list by different criteria: date of
    capture, nickname, pokedex number (see story #3)

## Analysis
TODO

## Architecture

We'll opt for the 3 layers (presentation, domain, data) of clean architecture.

### Design and Presentation Patterns

* MVVM
* Repository pattern

## Technologies

The project is using:
* Retrofit (remote API client)
* Dagger Hilt (dependencies injection)

TBC:
* ~~Navigation component (navigation between screens)~~
* ~~Room database (data persistance)~~
* ~~Jetpack Compose (UI)~~
* ~~Data Storage (settings)~~
* ~~Flow (live updates)~~
 
## Credits
* [Fran García](https://github.com/FranGarc), who motivated me to do this and from whom I shamelessly copied his readme from [his Pokedex repo](https://github.com/FranGarc/Pokedex/)
* [Agustín Ventura](https://github.com/agustinventura) for being our personal wikiman for all things architecture and development.

## License
Software developed by Jose Luis Montes Jiménez and released under the [GNU Public License v3](LICENSE.md)
Copyright (C) 2023  Jose Luis Montes Jiménez

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.