
# Docker Services
Common Daily Work Services

## Configuration

Change your environment settings in the .env file. \
 And, of course, make sure to create your .env file beforehand.

Example:

```bash
USER='my-user'
PASSWORD='myStrongerPassword'
MSSQL_PASSWORD='myStrongerBetterPassword'
...
```
Change the `docker-compose.services.yml` file according to your custom requirements.
## Usage

Clone the project

```bash
  git clone https://github.com/rodmedeiross/docker-services.git && cd docker-services
```


Run docker compose

```bash
  docker-compose -f docker-compose.services.yml up
```

