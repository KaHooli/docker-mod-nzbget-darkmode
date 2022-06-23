# DarkerNZBget theme - Docker mod for Plex

This mod adds the DarkerNZBget theme to NZBGet, to be downloaded/updated during container start.

More information, see [DarkerNZBget](https://github.com/ydkmlt84/DarkerNZBget/tree/develop).

In lscr.io/linuxserver/nzbget docker arguments, set an environment variable `DOCKER_MODS=ghcr.io/kahooli/nzbget-darkmode`.

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=ghcr.io/kahooli/nzbget-darkmode|linuxserver/mods:plex-mod2`.
