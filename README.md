# Step 1
Download and install docker desktop - https://www.docker.com/get-started/

# Step 2
Download the file docker-compose.yml from https://github.com/TheCouponBureau-org/pos-sdk-docker-compose/blob/71236e8f81576ef0f0ed0474d6c93eee374eddd6/docker-compose.yml

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

```
docker-compose up -d
```

# Step 5
Open your browser and go to http://localhost:3000/

# Step 6
If you want to stop the service, run the following command:

```
docker-compose down
```