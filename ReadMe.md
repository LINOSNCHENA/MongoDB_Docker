# COMMAND INSTRUCTIONS

## 1. Firewall Access
```
netsh advfirewall firewall add rule name="Allow Port 8080" dir=in action=allow protocol=TCP localport=8080
```

## 2. Runnning Port
```
http://localhost:8080/

```

## 3. Docker Manipulatitions
```
docker build -t linosnchena/node-app-ts .
docker images
docker run --name example-8080-image -p 80:8080 -d linosnchena/node-app-ts
```


## 4. Accounts
```
docker login -u linosnchena
docker stop e50ad27074a7
docker images -a


docker ps
docker tag a08f2c3169eb linosnchena/node-app-ts:latest
docker push linosnchena/node-app-ts
docker tag a08f2c3169eb linosnchena/node-app-ts:latest
docker push linosnchena/node-app-ts

```


## Access points

```
http://localhost:8080/
```


# End
