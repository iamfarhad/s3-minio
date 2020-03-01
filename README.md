# s3-minio

1. install docker-compose:

```bash
curl -L https://github.com/docker/compose/releases/download/1.25.4/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
```

2. pull minio image:

```bash
docker-compose pull
```

3. run image:

```bash
docker-compose up -d
```

the instance is now accessible on the host at ports 9004, proceed to access the Web browser at http://127.0.0.1:9004/

