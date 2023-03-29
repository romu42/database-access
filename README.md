Testing database access with go.

```
export DBUSER=user
export DBPASS=mypass
```

```docker run --name mariadb -e MYSQL_ROOT_PASSWORD=mypass -p 3306:3306 -d docker.io/library/mariadb:10.4```

#### Then follow the guide:
https://go.dev/doc/tutorial/database-access

#### you can also cheat a little and just run to get a local database with the sql table read in:
```docker compose up -d```



