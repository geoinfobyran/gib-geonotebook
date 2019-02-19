# Bouild

```
docker-compose build
```

# Run jupyter

```
docker-compose up
```

# Run bash

`jupyter` in the examples below refers to the service defined in [docker-compose.yml](docker-compose.yml)

## One time

```
docker-compose run jupyter /bin/bash
```

## Inside of runnign service

```
docker-compose exec jupyter /bin/bash
```


