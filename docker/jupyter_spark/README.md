# Jupyter Notebook + Spark

This is a folder when add a Jupyter Notebook with Spark.

First, Install Docker and [docker-compose](https://docs.docker.com/compose/install/) on your OS.

Then create your .env file:

```bash
cp .env_example .env
```

## Local setup

Now with your .env ready, you can execute the containers:

```bash
docker compose up
```

Let's access the Jupyter GUI interface, for that just type `http://localhost:8888/` on your browse.


By default, Jupyter UI don't have authentication.

