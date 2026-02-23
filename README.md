# wis2box-minio

This is a fork of the MinIO source-code that is archived at github.com/minio/minio. The source code is used to build a custom MinIO image for the WIS2BOX project. 

This fork is based of the tag=RELEASE.2024-08-03T04-33-23Z

The command to build the image is:

```
docker build -t wis2box-minio:latest -f Dockerfile.local --build-arg RELEASE=local-build-test .
```
