# Docker Compose for Node.js and PostgreSQL

## Run

    docker-compose up --build

## Test

```sh
curl http://localhost:3000/ping
# {"environment":"development","database":"up"}
```
## Create a new repository on the command line
echo "# nodejspostgre" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/onderyasarol/postgrenodejs.git
git push -u origin main

## Push an existing repository from the command line
git remote add origin https://github.com/onderyasarol/postgrenodejs.git
git branch -M main
git push -u origin main
