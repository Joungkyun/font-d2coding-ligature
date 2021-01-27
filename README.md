D2Coding Legature Web Fonts
====
[![D2Coding license](https://img.shields.io/badge/License-OFL-blue.svg)](https://raw.githubusercontent.com/Joungkyun/font-d2coding/master/license)

D2Coding Font who careted by [NAVER Corp](http://dev.naver.com/projects/d2coding).<br>
D2Coding Web Font who generated by [JoungKyun.Kim](http://oops.org/).

## License

___True Type font:___ Copyright &copy; NAVER Copr. All Rights Reserved.

OFL(Open Font License)

THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL THE
COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL
DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM
OTHER DEALINGS IN THE FONT SOFTWARE.

## Font information

### Weights
 * Bold (700)
 * Normal (400)

### Support type
 * eot
 * woff
 * woff2
 * ttf
 * svg

## Description

The [D2Coding](https://github.com/naver/d2codingfont) font is Korean developed font distributed by Naver. It is a font that is optimized for the coding of developers based on the well-known Nanum Barun Gothic font, considering not only the readability and similarity between characters but also harmony with Hangul in design.

The D2Coding font provides [ligature](https://en.wikipedia.org/wiki/Typographic_ligature) functionality since version 1.3. And because of the 50M restriction policy of jsdelivr, we branch out separately to the [D2Coding web font](https://github.com/Joungkyun/font-d2coding) repository.

For original and subset fonts, use the following repository:

- Origianl D2Coding Webfont: http://github.com/Joungkyun/font-d2coding
- Origianl D2Coding subset Webfont: http://github.com/Joungkyun/font-d2coding-subset
- D2Coding ligature subset Webfont: http://github.com/Joungkyun/font-d2coding-ligature-subset


## Installation

### 1. Using JSDelivr

Add the following code to the header section of the HTML document:

```html
<link href="http://cdn.jsdelivr.net/gh/joungkyun/font-d2coding-ligature/d2coding-ligature.css" rel="stylesheet" type="text/css">
```

Or, if you want to add a ___specific version___:

```html
<link href="http://cdn.jsdelivr.net/gh/joungkyun/font-d2coding-ligature@1.3.2/d2coding-ligature.css" rel="stylesheet" type="text/css">
```

### 2. Using download package

1. Uncompress the downloaded d2coding package into a web accessible path.
2. Add ___d2coding-ligature.css___ in the path to the header section of the HTML document as follow:

```html
<link href="/path/d2coding-ligature.css" rel="stylesheet" type="text/css">
```

### 3. Add font-face manually

In the header section of the HTML document, add CSS ___@font-face___ as follow:

```css
@font-face {
  font-family: 'D2 coding Ligature';
  font-style: normal;
  font-weight: 400;
  src: url('D2Coding-ligature.eot');
  src: local('※'), local('D2Coding ligature'),
       url('D2Coding-ligature.eot?#iefix') format('embedded-opentype'),
       url('D2Coding-ligature.woff2') format('x-woff2'),
       url('D2Coding-ligature.woff') format('woff'),
       url('D2Coding-ligature.ttf') format('truetype'),
       url('D2Coding-ligature.svg') format('svg');
}
@font-face {
  font-family: 'D2 coding Ligature';
  font-style: normal;
  font-weight: 700;
  src: url('d2codingbold-ligature.eot');
  src: local('※'), local('D2Coding ligature Bold'),
       url('D2CodingBold-ligature.eot?#iefix') format('embedded-opentype'),
       url('D2CodingBold-ligature.woff2') format('x-woff2'),
       url('D2CodingBold-ligature.woff') format('woff'),
       url('D2CodingBold-ligature.ttf') format('truetype'),
       url('D2CodingBold-ligature.svg') format('svg');
}

```

## Using

Adding to CSS:

```css
body {
	font-family: D2Coding ligature, 'D2 coding Ligature', monosapce;
}
```

first, search local ___D2Coding ligature font___ and next call ___D2 coding ligature web font___, and last load ___monospace___

