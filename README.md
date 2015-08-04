# API server in Go

Spiking an API server in Go.

# App Requirements

* PUT on /persons to store data about a person (only name, email address)
* If there is already a record, update. Otherwise, create.
* GET on /persons to get all persons (name only). Link to each item.
* GET on /person/1 gives name and email address of the person.

# Technical Requirements

* Go
* Deploy on Digital Ocean
* MongoDB - on Digital Ocean
* HAL JSON
* HAL browser
* Code Climate - badge
* Travis CI - badge
* Coveralls - badge
* New Relic monitoring
* ELK stack to monitor logs on Digital Ocean
