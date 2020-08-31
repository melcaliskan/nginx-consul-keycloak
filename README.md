# Using Nginx as reverse proxy with Consul and Keycloak(IAM)

```
docker-compose up
```
This command starts	 Nginx, Keycloak and PostgreSQL database.

The Nginx configuration can be found in `nginx.conf`.

Accessing [http://localhost:8080/auth/](http://localhost:8080/auth/) will open the administration UI of Keycloak. The credentials are "admin" and "password".

Accessing [http://localhost:8500/](http://localhost:8500/) will open Consul UI without any credentials.