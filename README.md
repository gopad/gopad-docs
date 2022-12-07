# Gopad: Documentation

[![General Workflow](https://github.com/gopad/gopad-docs/actions/workflows/general.yml/badge.svg)](https://github.com/gopad/gopad-docs/actions/workflows/general.yml) [![Codacy Badge](https://app.codacy.com/project/badge/Grade/68c1b27d8d864ad8a2e10d60773988f3)](https://www.codacy.com/gh/gopad/gopad-docs/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=gopad/gopad-docs&amp;utm_campaign=Badge_Grade) [![Join the Matrix chat at https://matrix.to/#/#gopad:matrix.org](https://img.shields.io/badge/matrix-%23gopad%3Amatrix.org-7bc9a4.svg)](https://matrix.to/#/#gopad:matrix.org)

Documentation for the Gopad  project including the related tools and clients,
you can find this website at [gopad.eu][website].

## Hosting

The website is hosted on [Netlify][netlify], the website gets
automatically updated on every push to the `master` branch.

## Install

This website uses the [Hugo][hugo] static site generator. If you are planning to
contribute you'll want to download and install Hugo on your local machine. The
installation of Hugo is out of the scope of this document, so please take the
[official install instructions][install] to get Hugo up and running.

## Development

To generate the website and serve it on [localhost:1313](http://localhost:1313)
just execute this command and stop it with `Ctrl+C`:

```console
make server
```

When you are done with your changes just create a pull request, after merging
the pull request the website will be updated automatically.

## Security

If you find a security issue please contact
[gopad@webhippie.de](mailto:gopad@webhippie.de) first.

## Contributing

Fork -> Patch -> Push -> Pull Request

## Authors

*   [Thomas Boerger](https://github.com/tboerger)

## License

CC-BY-SA-4.0

## Copyright

```console
Copyright (c) 2018 Thomas Boerger <thomas@webhippie.de>
```

[website]: https://gopad.eu
[netlify]: https://www.netlify.co
[hugo]: https://github.com/spf13/hugo
[install]: https://gohugo.io/overview/installing/
