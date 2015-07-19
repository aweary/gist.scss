# [gist.scss](http://aweary.github.io/gist.scss/)

## Summary

gist.scss lets you style embedded gists using SCSS. It's as simple as declaring all the required variables and importing the `gist.scss` file into your Sass project.

## Usage

You can download the raw file [here](https://raw.githubusercontent.com/Aweary/gist.scss/master/gist.scss), or you can install via `npm`.

```js
npm install --save gist.scss
```

Then you can just delcare the variables you want to use (described below), and import `gist.scss` to style all embedded gists on your page.

```scss
@import 'your_variables.scss';
@import 'gist.scss';
```


## Options

You declare all `gist.scss` options in a Sass map titled `$gist`. All the available options are optional (*badum-tsh*). You can find an example below.

```scss

$gist: (
  background: #FEFEFE,
  color: #333333,
  border: none,
  padding: 3em,
  colors: #FF44AA #AAFFAA #09ECDE #EFEFEF #5533EE #43EFFE,
  line-numbers-bg: #FEFEFE,
  line-numbers-color: #FF4444,
  line-numbers-border: none,
  meta-display: none,
);


```
