# [gist.scss](http://aweary.github.io/gist.scss/)

## Summary

gist.scss lets you style embedded gists using SCSS. It's as simple as declaring all the required variables and importing the `gist.scss` file into your Sass project.

## Usage
```scss
@import 'your_variables.scss';
@import 'gist.scss';
```

![gist.scss example](https://raw.githubusercontent.com/Aweary/gist.scss/master/docs/example.png)

## Options

You declare all `gist.scss` options in a Sass map titled `$gist`. All the available options are optional (*badum-tsh*).

```scss

$gist: (
  background: $paleyellow,
  color: $darkgray,
  border: none,
  padding: 3em,
  colors: $green $pink $cyan $blue $orange $blue,
  line-numbers-bg: $paleyellow,
  line-numbers-color: $green,
  line-numbers-border: none,
  meta-display: none,
);


```
