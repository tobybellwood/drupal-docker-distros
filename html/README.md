# Web UI

On a fresh Ubuntu/Debian x64 machine login as 'root' and run this:

```bash
curl -sS -o /tmp/server-install.sh https://raw.githubusercontent.com/theodorosploumis/drupal-docker-distros/master/scripts/server-install.sh
/bin/sh /tmp/server-install.sh

```

This will install the Web UI on a server with main domain "distros.bid" and container subdomain "drupal.distros.bid".

 - Tested with Debian 9.2 x64.
 - Needs at least 8GB of RAM
 - Docker images need at least 50GB space
