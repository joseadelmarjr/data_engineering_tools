# Data Engineer Tools

An [Airflow](https://m.signalvnoise.com/the-majestic-monolith/) based environment to create, test and deploy data pipelines.

- [Local Setup](#local-setup)
- [Development](#development)
- [Contribution Guide](#contribution-guide)

## Local Setup

We are using [docker-compose](https://docs.docker.com/compose/) like a container orchestration for the airflow(web-server, schedule and workers), Postgres(back-end database), redis(communication between schedule and workers) and minio(for the local S3). Please follow these steps:

First, Install Docker and [docker-compose](https://docs.docker.com/compose/install/) on your OS.

Then create your .env file:

```bash
cp .env_example .env
```

By default, Airflow user and password will be admin / admin.

## Local setup

Now with your .env ready, you can execute the containers:

```bash
docker compose up
```

This will download the images and run the containers for us, to check if all is fine, just execute:

```bash
docker ps
```

Please check that all the containers have the status Up.

All done, the folder structure will be created. Follow the several conventions:

- All Python code must be on the `dags/` folder;
- Other scripts types must be on the `include/` folder.

Let's access the airflow GUI interface, for that just type `http://localhost:8080/` on your browse.

From use VsCode directly to container, add the remote container feature in this [link](https://code.visualstudio.com/docs/remote/containers).

## Installing dependencies

In case you decide to add another Python library to Airflow, you need to add it to the `requirements.txt` file of the corresponding environment in the `requirements/` folder.

Libraries in the `requirements/requirements.txt` file are loaded by all environments.

Libraries in the `requirements/requirements_lint.txt` file are loaded by the _development_ environment and dedicatedly used during CI linting steps.

## Contribution Guide
TBD

**Welcome to Data Engineer Tools!**
*Data engineering team*
