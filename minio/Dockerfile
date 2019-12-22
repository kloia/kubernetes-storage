FROM minio/minio
ENV MINIO_ACCESS_KEY ACCESS_KEY
ENV MINIO_SECRET_KEY SECRET_KEY

ENTRYPOINT mkdir -p /storage/backupbucket && exec /usr/bin/minio server /storage
