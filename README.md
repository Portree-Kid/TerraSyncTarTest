# TerraSyncTarTest
DockerFile &amp; HTTP Server content to test tar download proposal

Build image 

```
docker build C:\git\TerraSyncTarTest\ -t terrasync
```

Run image with local port 1181 forwarded to container. The tests in TerraMaster use 1181

```
docker run -p 1181:80 terrasync
```

Models/.dirindex

```
version:1
path:Models
t:Effects:5f7f4e57286a65b5fb28cdb4dd46cab4454184c8:416
```

Points to Models/Effects.tgz

.dirindex in Objects/w010n70

```
version:1
path:Objects/w010n70
t:w009n70:86eb1bd1f20f8f8c444d70a4c463f192415bd526
```

