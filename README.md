# README

This project is Docker and rails app format.<br>
Please use this freely.

### Step 1. Create Docker Image
Let's create a Docker image.

```
docker-compose build
```

### Step 2. Start  Docker Container
Let's start the Docker container.

```
docker-compose up
```

### Step 3. Create Database
Let's create a database for rails.

```
docker-compose run web rake db:create
```

### <font color="Navy">※ reference</font><br>
https://docs.docker.com/samples/rails/

<br>
Have a nice development !
