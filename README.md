# Docker LAMP
Linux + Apache + MariaDB (MySQL) + PHP 7.2 on Docker Compose. Mod_rewrite enabled by default.

## FORKED BY: Etienne Jacquot - 01/26/21 epj@asc.upenn.edu

Testing for NDG web php applications + developer Alan Wagner

- trying to incorporate steps from here into a docker build https://github.com/alanwagner/FhSiteKit

``` bash
cd docker-lamp

```


there is the `vendor/` directory ...

there is also the `app/config/`, I think some of these files are composer created though ...

## Instructions

Enter the following command to start your containers:
```bash
$ docker-compose up -d
```

To stop them, use this:
```bash
$ docker-compose stop
```

Feel free to make pull requests and help to improve this.

If you are looking for phpMyAdmin, take a look at [this](https://github.com/celsocelante/docker-lamp/issues/2).
