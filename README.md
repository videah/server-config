# My Server Config

This repo contains various docker related files that make up the infrastructure
hosted on [videah.net](https://videah.net). This is mostly just for my own personal
use but if you find anything useful I hope it helps!

 - `caddy` - My reverse proxy. This handles automatically proxying DNS to containers and renewing certs using docker labels
 - `twitter-api-proxy` - Very small proxy for the Twitter API I use to make iOS shortcuts
 - `videah.net` - My personal website hosted at [videah.net](https://videah.net), also manages some redirects
 - `watchtower` - Scans for changes to my Docker Hub images and automatically recreates containers when it detects an update
 - `whoami` - Test container used as a Hello World for the server