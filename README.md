make sure docker is running

copy .env.example to .env

open terminal bash or cmd, go to folder

run:
```
docker-compose -f docker-compose.yml up -d
```

connect to mysql using:

```
host: 127.1.1.1
username: test
password: secret
```

or if changes has been applied to .env
