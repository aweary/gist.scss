# [gist.scss](http://aweary.github.io/gist.scss/)

gist.scss lets you style embedded gists using SCSS. It's as simple as declaring all the required variables and importing the `gist.scss` file into your Sass project.

```scss
@import 'your_variables.scss';
@import 'gist.scss';
```
Remember that these variables are not initialized anywhere yet. See below for more details. Below is an example of a styled embedded Gist.

![gist.scss example](https://raw.githubusercontent.com/Aweary/gist.scss/master/docs/example.png)

## Variables

These variables are all required to be initialized. They are not placed
within gist.scss so that anyone can easily add them to their _variables.scss file
or manage their varibales however they like.


```scss


$gist-border              /* Border style for embedded gist */
$gist-meta-display        /* Display property for the meta section at the bottom  */
$gist-meta-bg             /* Meta section background color */
$gist-meta-color          /* Meta section font folor */
$gist-bg                  /* Primary background gcolor */
$gist-color               /* Primary text color */
$gist-line-number-bg      /* Primary line number background */
$gist-line-number-color   /* Primary line number color */


$first-color              /* The seven different classes used for element styles */
$second-color
$third-color
$fourth-color
$fifth-color
$sixth-color
$seventh-color

```
