# Usage

after cloning the repository;

first build java app from source
```sh
cd module_2_management

mvn -Dmaven.test.skip=true package
```

fill and rename `.env.db.sample` file as requested inside

if you want to run this project in raspberry pi you should run this command 
```sh
docker-compose -f docker-compose-pi.yml up --build
````

otherwise you should run
```sh
docker-compose up --build
```