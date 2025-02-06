# Step 1
Download and install docker desktop - https://www.docker.com/get-started/

# Step 2
Download the file docker-compose.yml from https://github.com/TheCouponBureau-org/pos-sdk-docker-compose/blob/86a9c5bab8d43f3fff4593e474fc60c7d2e438ea/docker-compose.yml

# Step 3
Open terminal or command prompt and go to the folder where you downloaded docker-compose.yml file.

# Step 4
Run the following command:

```
docker login
```
username: thecouponbureau
password: TCB123$$%%

After login, you will see Login succeeded message in the terminal.

# Step 5
Run the following command to start the service:

```
docker-compose up -d
```

# Step 6
Open your browser and go to http://localhost:3000/

# Step 7
If you want to stop the service, run the following command:

```
docker-compose down
```

# Step 8
If you want to see logs of the service, run the following command:

```
docker logs -f --tail 100 pos-sdk
