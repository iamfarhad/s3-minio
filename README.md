# s3-minio

1. install docker-compose:
```bash
sudo apt-get install docker-compose
```

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

if you want change default access key and secret key you can use this environment

```bash
      MINIO_ACCESS_KEY: new
      MINIO_SECRET_KEY: new123
      MINIO_ACCESS_KEY_OLD: minio
      MINIO_SECRET_KEY_OLD: minio123
```


