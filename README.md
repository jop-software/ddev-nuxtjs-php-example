# DDEV NuxtJS <-> PHP Example

This is a example DDEV Setup for development with a NuxtJS Frontend and a PHP Backend.

## Professional Support
Professional / Enterprise support is available. Please contact [mailto:info@jop-software.de](info@jop-software.de) for more information.

## Start

```bash
ddev start
```

## How does this work?

There is a NuxtJS example setup with a custom `Dockerfile` in `web/frontend`.
The Dockerfile is added as a service in `.ddev/docker-compose.frontend.yaml` which also adds a volume and overwrite the `CMD` directive to allow for live reloading.

## Production Setup

I'd suggest to load the web/backend and web/frontend from separate git repositories.


&copy; 2022, jop-software Inh. Johannes Przymusinskis