# tryfly
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


-----------------------
=== Fetching app code
=== Building web (Dockerfile)
Sending build context to Docker daemon  6.144kBStep 1/3 : FROM v2fly/v2fly-core
latest: Pulling from v2fly/v2fly-core
df9b9388f04a: Pulling fs layer
4f4fb700ef54: Pulling fs layer
81209e08b3b3: Pulling fs layer
884be9465574: Pulling fs layer
884be9465574: Waiting
81209e08b3b3: Verifying Checksum
81209e08b3b3: Download complete
df9b9388f04a: Download complete
4f4fb700ef54: Verifying Checksum
4f4fb700ef54: Download complete
df9b9388f04a: Pull complete
884be9465574: Verifying Checksum
884be9465574: Download complete
4f4fb700ef54: Pull complete
81209e08b3b3: Pull complete
884be9465574: Pull complete
Digest: sha256:66470ecb177e83203c6124ad65470f9fcc9b2c8d65efb55b0516f50bde55e36e
Status: Downloaded newer image for v2fly/v2fly-core:latest
 ---> 606927910534
Step 2/3 : ENV TZ=Asia/Shanghai
 ---> Running in 8245aacb8391
Removing intermediate container 8245aacb8391
 ---> 74f4fd89a289
Step 3/3 : ADD entrypoint.sh /
 ---> 9c1646df35b9
Successfully built 9c1646df35b9
Successfully tagged 84d9a9fa0d9156c90c3e37c040257d1b3fd4e2ef:latest
=== Pushing web (Dockerfile)
Tagged image "84d9a9fa0d9156c90c3e37c040257d1b3fd4e2ef" as "registry.heroku.com/fkdufejf/web"
Using default tag: latest
The push refers to repository [registry.heroku.com/fkdufejf/web]
ac1bc6f94f86: Preparing
bcdfc7270960: Preparing
23882abf7acf: Preparing
5f70bf18a086: Preparing
4fc242d58285: Preparing
5f70bf18a086: Pushed
23882abf7acf: Pushed
4fc242d58285: Pushed
ac1bc6f94f86: Pushed
bcdfc7270960: Pushed
latest: digest: sha256:0c65e99bdb449c578ed437369b9899fce6e1fc76e5c2617c91e2f8d03a792da2 size: 1360
