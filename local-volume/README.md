```bash
docker run \
-p 80:3000 \
--name express-app \
-v $(pwd)/public:/usr/src/app/public \
express-app

docker kill express-app && docker rm express-app
```
