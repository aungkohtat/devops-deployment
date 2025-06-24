##### build Docker image called node-app. Execute from root

   
   ```
   docker build -t node-app .
   ```


    docker run -d -p 3000:3000 --name my-node-container node-app 
    
```
docker run -p 27017:27017 -d -e MONGO_INITDB_ROOT_USERNAME=admin -e MONGO_INITDB_ROOT_PASSWORD=password --name mongodb --net mongo-network mongo
```

```
docker run -d \
  -p 8081:8081 \
  -e ME_CONFIG_MONGODB_ADMINUSERNAME=admin \
  -e ME_CONFIG_MONGODB_ADMINPASSWORD=password \
  --net mongo-network \
  --name mongo-express \
  -e ME_CONFIG_MONGODB_SERVER=mongodb \
  mongo-express 
```

![](./imgs/Screenshot%202025-06-24%20at%204.55.50 PM.png)

![](./imgs/Screenshot%202025-06-24%20at%204.57.04 PM.png)


