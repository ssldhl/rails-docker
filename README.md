# Rails Docker
Docker Compose to set up and run a Rails/PostgreSQL app

Build
--

* Project

```
docker-compose run web rails new . --force --no-deps --database=postgresql
```

* Rebuild

```
docker-compose build
```

* Connect the database

```
Replace the contents of config/database.yml
```

* Boot

```
docker-compose up
```

* Create the database

```
docker-compose run web rake db:create
```

* Test

```
Visit http://localhost:3000
```
