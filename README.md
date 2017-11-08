# verbum theme [![](https://badge.fury.io/js/jsonresume-theme-verbum.svg)](https://www.npmjs.org/package/jsonresume-theme-verbum)

This is the verbum theme for [JSON Resume](http://jsonresume.org/).


![Preview of verbum theme](https://raw.githubusercontent.com/konalexiou/jsonresume-theme-verbum/master/verbum.png)

## Getting started

To get started with theme development, this is what you'll need:

- [node.js](http://howtonode.org/how-to-install-nodejs)
- [npm](http://howtonode.org/introduction-to-npm)

If you're on Linux, you can simply run:

```
sudo apt-get install nodejs-legacy npm
```

Or if you're on OSX and got [Homebrew](http://brew.sh/) installed:
```
brew install node
```

### Install the command line

We're going to use the official [resume-cli](https://github.com/jsonresume/resume-cli) to run our development server.

Go ahead and install it:

```
sudo npm install -g resume-cli
```

### Install theme

Install the theme by typing
```bash
npm install -g jsonresume-theme-verbum
```

### Work on your resume

If you don't already have your json resume you can make in online by visiting:
http://registry.jsonresume.org/

### Publish json resume

If you want to publish your resume, first copy your resume.json and then run:

```bash
resume publish --theme=verbum
```

### Export json resume in PDF

If you want to publish your resume, first copy your resume.json and then run:

```bash
resume export resume.pdf --theme=verbum
```

## License

Available under [the MIT license](http://mths.be/mit).
