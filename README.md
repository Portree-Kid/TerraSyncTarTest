# TerraSyncTarTest
DockerFile &amp; HTTP Server content to test tar download proposal

Build image 

```
docker build C:\git\TerraSyncTarTest\ -t terrasync
```

Run image with local port 1181 forwarded to container. The tests in TerraMaster use 1181

The example contains normal terrasync directories mixed with new style tarballs.

```
docker run -p 1181:80 terrasync
```

Buildings/w090n20/w081n23/.dirindex

```
version:1
path:w090n20/w081n23
f:1629251.stg:463d76179fe9a797b1d986f79ac0ec17bfcea042:268
f:1629256.stg:28324511760a4c36fd7be6802866844cb0cb0497:268
f:1629258.stg:df859cbcbface2a8a770e6997a8fb9966fbcca0e:268
t:w090n20_w081n23_buildings.tgz:ffb072e3c671360a8a0787a0724c5d1310749acf:327
f:1629249.stg:7ccd0f2b7979beb0c0f2f23bb28b00348677d905:268
```

Where w090n20_w081n23_buildings.tgz extracts as follows.

```
w090n20_w081n23_buildings/
w090n20_w081n23_buildings/w090n20_w081n23_1629251_buildings_shader.txt
w090n20_w081n23_buildings/w090n20_w081n23_1629249_buildings_shader.txt
w090n20_w081n23_buildings/w090n20_w081n23_1629258_buildings_shader.txt
w090n20_w081n23_buildings/w090n20_w081n23_1629256_buildings_shader.txt
```