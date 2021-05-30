

# Dev Docker Image

```
docker-compose up -d dev
docker-compose exec dev zsh
```

* mounts ./dev:/root/dev

## Newman

* https://github.com/postmanlabs/newma
* usage:
```
newman run examples/sample-collection.json
```