# docs.rockylinux.org

[![Website](https://img.shields.io/website?url=https%3A%2F%2Flearn.rockylinux.org)](https://learn.rockylinux.org)
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/rocky-linux/learn.rockylinux.org/main.svg)](https://results.pre-commit.ci/latest/github/rocky-linux/learn.rockylinux.org/main)

The Rocky Linux learning platform + documentation site, built using
[Hugo](https://gohugo.io) and [TailwindCSS](https://tailwindcss.com).

## Getting Started

### Requirements

This project requires that [Hugo](https://gohugo.io) and
[NodeJS](https://nodejs.org) be installed on your computer.

Project dependencies are controlled by `npm`, so you can run `npm install` to
download and install those into the project folder.


### Working on the Project

For the most part, you'll want to be able to preview your changes as you make
edits to the site. You can use the NPM script `start` to do this:

```
$ npm install # ensure dependencies are installed...
$ npm start # start the hugo dev server...
```

If you wish to compile the site into plain HTML/CSS/JS to load into a static
web server, however, you can run:

```bash
$ npm install --production # ensure production dependencies are installed...
$ npm run build # build the hugo site...
```

The folder `public/` will be created, and populated with the compiled Hugo
site.

## Contributing

Contributions are *always* welcome. See [CONTRIBUTING.md](./CONTRIBUTING.md)
for our guidelines on how you should do that!
