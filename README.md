# tryfly
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


-----------------------
=== Fetching app code

=== Building web (Dockerfile)

Sending build context to Docker daemon  6.144kBStep 1/3 : FROM v2fly/v2fly-core

latest: Pulling from v2fly/v2fly-core


Status: Downloaded newer image for v2fly/v2fly-core:latest

Step 2/3 : ENV TZ=Asia/Shanghai

Removing intermediate container 8245aacb8391

Step 3/3 : ADD entrypoint.sh /

Successfully tagged 84d9a9fa0d9156c90c3e37c040257d1b3fd4e2ef:latest

=== Pushing web (Dockerfile)

Tagged image "84d9a9fa0d9156c90c3e37c040257d1b3fd4e2ef" as "registry.heroku.com/fkdufejf/web"

Using default tag: latest

The push refers to repository [registry.heroku.com/fkdufejf/web]

latest: digest: sha256:0c65e99bdb449c578ed437369b9899fce6e1fc76e5c2617c91e2f8d03a792da2 size: 1360
