Start the Panel:
 
docker-compose up -d
 
Create a user for the panel:
 
docker-compose run --rm panel php artisan p:user:make

make sure to make port 8080 public