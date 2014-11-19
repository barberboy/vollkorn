Vollkorn
========
Quickly use the [Vollkorn] typeface in your project.


About
-----
Vollkorn is the fabulous full-featured typeface designed by Friedrich Althausen
“for bread and butter use.” It comes in eight styles, supports all european
languages, and features multiple figure sets, ligatures, contextual alternates,
and other OpenType features.

Vollkorn is available for personal or commercial use under the SIL Open Font
License. “[Pay what you want][donate]” to say thanks and support its continued
development.


Usage
-----
You have several options for using this project:

### Clone with git

```sh
cd styles/fonts
git clone https://github.com/barberboy/Vollkorn
```

```html
<link rel="stylesheet" href="/styles/fonts/Vollkorn/vollkorn.css">
```


### Download

Download and unpack the [.zip archive](https://github.com/barberboy/Vollkorn/archive/master.zip):

```sh
cd styles/fonts
wget https://github.com/barberboy/Vollkorn/archive/master.zip
unzip master.zip
mv Vollkorn-master Vollkorn
rm master.zip
```

```html
<link rel="stylesheet" href="/styles/fonts/Vollkorn/vollkorn.css">
```


### Bower

```sh
bower install barberboy/Vollkorn
```

```html
<link rel="stylesheet" href="/bower_components/Vollkorn/vollkorn.css">
```

If you’d like bower to put it in a different directory, just create a
[`.bowerrc`](http://bower.io/docs/config/) file and specify the
[`directory`](http://bower.io/docs/config/#directory) location:

```json
{
  "directory": "app/public",
  "analytics": false
}
```

### CDN

Quickly test Vollkorn on your site by using the CDN hosted by [RawGit]. Feel
free to use it in production as well:

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/barberboy/Vollkorn/3.0.0.5/vollkorn.css">
```

### Google Fonts

Not for you? Just use Google Fonts instead:

```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Vollkorn:400italic,700italic,400,700">
```


Styles and Weights
-----------------
This project includes regular and italic styles in four different weights. Use
what you’d like:

```css
body {
  font-family: 'Vollkorn';
  font-weight: 400;

  font-family: 'Vollkorn';
  font-weight: 500;

  font-family: 'Vollkorn';
  font-weight: 600;

  font-family: 'Vollkorn';
  font-weight: 700;
}
```


### OpenType Features
Vollkorn supports several [OpenType features], including liga, dlig, calt, salt,
kern, ss01, lnum, onum, pnum, tnum, frac. Turn on whichever features you’d like:

```css
h1 {
  font-family: Vollkorn;
  -webkit-font-feature-settings: "locl" 1, "sups" 1, "numr" 1, "dnom" 1, "frac" 1, "ordn" 1, "lnum" 1, "pnum" 1, "tnum" 1, "onum" 1, "dlig" 1, "liga" 1, "calt" 1, "case" 1, "salt" 1, "ss01" 1, "cpsp" 1;
  -moz-font-feature-settings: "locl" 1, "sups" 1, "numr" 1, "dnom" 1, "frac" 1, "ordn" 1, "lnum" 1, "pnum" 1, "tnum" 1, "onum" 1, "dlig" 1, "liga" 1, "calt" 1, "case" 1, "salt" 1, "ss01" 1, "cpsp" 1;
  -moz-font-feature-settings: "locl=1, sups=1, numr=1, dnom=1, frac=1, ordn=1, lnum=1, pnum=1, tnum=1, onum=1, dlig=1, liga=1, calt=1, case=1, salt=1, ss01=1, cpsp=1";
  -ms-font-feature-settings: "locl" 1, "sups" 1, "numr" 1, "dnom" 1, "frac" 1, "ordn" 1, "lnum" 1, "pnum" 1, "tnum" 1, "onum" 1, "dlig" 1, "liga" 1, "calt" 1, "case" 1, "salt" 1, "ss01" 1, "cpsp" 1;
  -o-font-feature-settings: "locl" 1, "sups" 1, "numr" 1, "dnom" 1, "frac" 1, "ordn" 1, "lnum" 1, "pnum" 1, "tnum" 1, "onum" 1, "dlig" 1, "liga" 1, "calt" 1, "case" 1, "salt" 1, "ss01" 1, "cpsp" 1;
  font-feature-settings: "locl" 1, "sups" 1, "numr" 1, "dnom" 1, "frac" 1, "ordn" 1, "lnum" 1, "pnum" 1, "tnum" 1, "onum" 1, "dlig" 1, "liga" 1, "calt" 1, "case" 1, "salt" 1, "ss01" 1, "cpsp" 1;
}
```

[RawGit]: https://rawgit.com/
[Vollkorn]: http://vollkorn-typeface.com/
[Donate]: http://vollkorn-typeface.com/#donate
[OpenType Features]: http://www.microsoft.com/typography/otspec/featurelist.htm