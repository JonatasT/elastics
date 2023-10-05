# elastics

### After cloning repo...

## Running:

Run the following code to up docker container to prepare the elasticsearch instance:

```
docker compose up -d
```

Make sure this docker container ir running and access the :9200 port in your browser.


## Stopping:

```
docker compose down
```

Ps.: If you needs to change another resources and settings for the docker instance, handle the **docker-compose.yml** file.