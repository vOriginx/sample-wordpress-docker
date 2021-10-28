To get started, simply run `docker-compose up --build -d` to run the containers in a detached mode.

All database data will be stored in the local `db_data` folder to persist your wordpress install.

All web files will be synced with the local `wordpress` folder to persist web file changes.

To stop the containers simply run `docker-compose stop`.

To remove the containers (this will delete all data in the containers) run `docker-compose down`.