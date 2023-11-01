# minio-healthcheck-reproducer

- `docker-compose up`
- verify whether the container comes up and stays up, or if it fails healthchecks: `docker ps`
- compare with an older release: `MINIO_RELEASE=RELEASE.2023-09-20T22-49-55Z docker-compose up`
