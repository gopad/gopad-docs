# Gopad: Documentation

[![Build Status](http://github.dronehippie.de/api/badges/gopad/gopad-docs/status.svg)](http://github.dronehippie.de/gopad/gopad-docs)
[![Stories in Ready](https://badge.waffle.io/gopad/gopad-api.svg?label=ready&title=Ready)](http://waffle.io/gopad/gopad-api)
[![Join the Matrix chat at https://matrix.to/#/#gopad:matrix.org](https://img.shields.io/badge/matrix-%23gopad%3Amatrix.org-7bc9a4.svg)](https://matrix.to/#/#gopad:matrix.org)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/6012a233d1e04981bb8d078510cacb2b)](https://www.codacy.com/app/gopad/gopad-docs?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=gopad/gopad-docs&amp;utm_campaign=Badge_Grade)
[![](https://images.microbadger.com/badges/image/gopad/gopad-docs.svg)](http://microbadger.com/images/gopad/gopad-docs "Get your own image badge on microbadger.com")


Documentation for the Gopad project, you can find this website at [gopad.webhippie.de](https://gopad.webhippie.de).


## Hosting

The website is hosted on infrastructure sponsored by [Webhippie](https://webhippie.de). The website gets automatically updated on every push to the `master` branch.

If you want to host the docs on your own you can take our docker image [gopad/gopad-docs](https://hub.docker.com/r/gopad/gopad-docs/).


## Install

This website uses the [Hugo](https://github.com/spf13/hugo) static site generator. If you are planning to contribute you'll want to download and install Hugo on your local machine.

The installation of Hugo is out of the scope of this document, so please take the [official install instructions](https://gohugo.io/overview/installing/) to get Hugo up and running.


## Development

To generate the website and serve it on [localhost:1313](http://localhost:1313) just execute this command and stop it with `Ctrl+C`:

```
make server
```

When you are done with your changes just create a pull request, after merging the pull request the website will be updated automatically.


## Security

If you find a security issue please contact thomas@webhippie.de first.


## Contributing

Fork -> Patch -> Push -> Pull Request


## Authors

* [Thomas Boerger](https://github.com/tboerger)


## License

CC-BY-SA-4.0


## Copyright

```
Copyright (c) 2018 Thomas Boerger <thomas@webhippie.de>
```
