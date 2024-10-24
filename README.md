# Open Web Analytics on Docker

This repo can be used to deploy [Open Web Analytics](http://www.openwebanalytics.com/) on Docker.

- It uses the official [Open Web Analytics](https://github.com/Open-Web-Analytics/Open-Web-Analytics) installation package with the official [PHP with Apache Docker image](https://hub.docker.com/_/php) as the base runtime.
- It uses [MySQL](https://hub.docker.com/_/mysql) for the database.

## Deployment
* **Enviroment Variables:**

| Key | Value |
| --- | --- |
| OWA_DB_HOST | The hostname from the MySQL database |
| OWA_DB_NAME | The database name from the MySQL database |
| OWA_DB_USER | The username from the MySQL database |
| OWA_DB_PASSWORD | The password from the MySQL database |
| OWA_DB_PORT | Originally 3306 |
| OWA_AUTH_KEY | Use your own |
| OWA_AUTH_SALT | Use your own |
| OWA_NONCE_KEY | Use your own |
| OWA_NONCE_SALT | Use your own |
