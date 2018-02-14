# Ruby on Rails // Docker

- Simple application that uses CRUD with the web framework Ruby on Rails
- Docker was used to containerize this application
- Tested on a local environment (macOS) and was never deployed to a cloud service

## Docker commands

docker-compose up    
docker-compose up --build    
docker-compose run web bundle install    
docker-compose run web rake db:create    
docker-compose run web rake db:migrate    
docker-compose run web rake routes    

tmp/pids/server.pid

Rails -> Generate Models
docker-compose run web rails generate model "Noun"    
docker-compose run web rails generate controller "Noun"    

## Screenshots
![ScreenShot](https://github.com/du3ly/myapp/blob/master/images/Screen%20Shot%202018-02-01%20at%2010.40.15%20PM.png)
![ScreenShot](https://github.com/du3ly/myapp/blob/master/images/Screen%20Shot%202018-02-01%20at%2010.40.26%20PM.png)
![ScreenShot](https://github.com/du3ly/myapp/blob/master/images/Screen%20Shot%202018-02-01%20at%2010.40.37%20PM.png)
