# trailbud

MVP:
MERN stack using create react app that allows user to create, read, update and delete overlanding trails and comments on those trails styled with bootstrap

Stretch goals:
Search feature, with filters by distance, length, ect...
Implement google maps
Authentication

Components:
Trails - Location, length, difficulty, description
Comments

create react app

react/php/laravel/postgres
angular

trails table:
name, location, description, length


SCHEDULE:

Thurs 2/4  - Make a schedule
Fri   2/5  - Study PHP
Sat   2/6  - Study PHP
Sun   2/7  - Study PHP
Mon   2/8  - Update php version
Tues  2/9  - complete backend
Wed   2/10 - complete frontend
Thurs 2/11 - MVP Delployed on heroku
Fri   2/12 - Add google maps
Sat   2/13 - Add search feature/Auth
Sun   2/14 - CSS styling
Mon   2/15 - minor touch ups
Tues  2/16 - PRESENTATION

PHP version: 8.0.0





SEED DATA:

CREATE TABLE trails (id SERIAL, name VARCHAR(25), location VARCHAR(50), description VARCHAR(250), length INT);
INSERT INTO trails (name, location, description, length) VALUES ('The Rubicon', 'Sierra Nevada', 'Legendary trail in the Sierra Nevada mountains', 22);

composer.json file correct? --- composer init
.env.example file correct??

