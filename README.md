# API Star Wars <img src="https://cdn.worldvectorlogo.com/logos/star-wars-4.svg" width="50" height="50">

https://api-star-wars-pulsus.herokuapp.com/

Rails app generated with [lewagon/rails-templates](https://github.com/lewagon/rails-templates), created by the [Le Wagon coding bootcamp](https://www.lewagon.com) team.

It's a app using **Ruby on Rails, HTML, CSS, Bootstrap and Active Record**. 

⭐ MODELOS ⭐

- rails g model character name height mass birth_year
- rails g model planet name rails g model film title
- rails g model vehicle name model 
- rails g model starship name model 
- rails g model category name 
- rails g migration AddPlanetToCharacters planet:references 
- rails g migration AddCateogryToCharacters category:references
- rails g migration CreateJoinTableCharacterFilm character film 
- rails g migration CreateJoinTableCharacterVehicle character vehicle 
- rails g migration CreateJoinTableCharacterStarship character starship

The caracthers model has a method to send a full feed message through an API database https://swapi.dev/

RUN:
-bundle
-yarn

rails db:drop db:create db:migrate db:seed 🌱🌱🌱🌱🌱

https://api-star-wars-pulsus.herokuapp.com/
QUE A FORÇA ESTEJA COM VOCÊ!
<img src="data:image/jpeg;base64,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" width="50" height="50">
