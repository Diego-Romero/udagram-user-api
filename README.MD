# to run

```
docker run \
-e POSTGRES_USERNAME=postgres  \
-e POSTGRES_PASSWORD=totallynotmypassword \
-e POSTGRES_HOST=database.ctxaw5xe1d4f.eu-west-2.rds.amazonaws.com \
-e POSTGRES_DB=udagram \
-e AWS_BUCKET=udacity-cloud-developer-diego \
-e AWS_REGION=eu-west-2 \
-e AWS_PROFILE=default \
-e JWT_SECRET=helloworld \
-e URL=http://localhost:8080 \
-e PORT=8200 \
-p 8200:8200 feed-api
```
