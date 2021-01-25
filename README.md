# WorkAdventure

## Cloning the repository

We include our maps as a submodule, therefore the git clone command changes to:

```
git clone --recurse-submodules -b fswiai-development git@github.com:fs-wiai/workadventure.git
```

Production code is on branch `fswiai-production`.

## Getting started

Install Docker.

Run:

```
docker-compose up
```

The environment will start.

You should now be able to browse to http://workadventure.localhost/ and see the application.

Note: on some OSes, you will need to add this line to your `/etc/hosts` file:

**/etc/hosts**
```
workadventure.localhost 127.0.0.1
```