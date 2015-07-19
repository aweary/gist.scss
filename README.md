# [gist.scss](http://aweary.github.io/gist.scss/)

gist.scss lets you style embedded gists using SCSS. It's as simple as declaring all the required variables and importing the `gist.scss` file into your Sass project.

```scss
@import 'your_variables.scss';
@import 'gist.scss';
```
Remember that these variables are not initialized anywhere yet. See below for more details. Below is an example of a styled embedded Gist.

![gist.scss example](https://raw.githubusercontent.com/Aweary/gist.scss/master/docs/example.png)

## Variables

You declare all `gist.scss` options in a Sass map titled `$gist`. All the available options are optional (*badum-tsh*).
Make sure this included or declared before `gist.scss`.

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
