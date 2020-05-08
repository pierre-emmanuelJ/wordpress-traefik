# wordpress-traefik
WordPress with Traefik in Docker and docker-compose

## Installation

Clone the repo
```Shell
$ git clone https://github.com/pierre-emmanuelJ/wordpress-traefik.git
```
```Shell
$ cd wordpress-traefik
```
```Shell
$ mkdir data
```
```Shell
$ touch acme.json && chmod 600 acme.json
```

In `docker-compose.yml` and `traefik.toml` replace all `example.com` by your desired domain.

In `docker-compose.yml` replace all `password_example` by your desired database password.

Run it now

```Shell
$ docker-compose up -d
```

```Shell
$ sudo chown -R www-data ./data/www
```

### FINISH

Browse https://example.com/wp-admin/install.php to setup your WordPress :rocket:

![image](https://i.imgur.com/JpfTVYM.png)

## Enjoy
