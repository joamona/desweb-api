# DESWEB-API
Docker Django API template

# Help

- Clone the repo:

```ruby
    git clone https://github.com/joamona/desweb-api.git
```

- Change to the project folder:
```ruby
    cd desweb-api
```
- Create the pgadmin folders:
```ruby
    Windows: pgadmin_create_folders_windows.bat
    Linux: ./pgadmin_create_folders_linux.sh
```
- Create the containers and start the services:
```ruby
    docker compose up
```
- Check the services:

    - pgadmin: http://localhost:8050
    - geoserver: http://localhost:8080
    - Django API: http://localhost:8000

