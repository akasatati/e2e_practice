# e2e_practice
CodeceptJSで色々やってみる

## SetUp
```
cp .env.example .env
cp conf/credentials.example.js conf/credentials.js 
cp conf/environments.example.js conf/environments.js

docker-compose build

# Sample Command
time docker-compose run --rm codeceptjs codeceptjs run --grep '(?=.*@fujiya)' --steps --verbose
```
