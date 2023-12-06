# Assignment 3 - Part 2

## File Locations

```
/var/www
├── backend
│   └── hello-server
├── html
│   └── index.nginx-debian.html
└── my-site
    └── index.html

/etc/nginx
# other files omitted
├── nginx.conf
├── sites-available
│   ├── default
│   └── hello.conf
├── sites-enabled
│   └── hello -> /etc/nginx/sites-available/hello.conf
├── snippets
│   ├── fastcgi-php.conf
│   └── snakeoil.conf
├── uwsgi_params
└── win-utf

/etc/systemd/system
├── hello-server.service

```