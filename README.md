# HTML5 Test
The website is created for a HTML5 Test of Integrify programme. The question can be found [here](https://github.com/digiaonline/docs/tree/master/recruitment/html5)

## Code Example
Here are some lines of example code:
1. index.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>HTML5 test app</title>
    <!-- Link to Google fonts -->
    <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
    <!-- Link to main.css -->
    <link rel="stylesheet" href="css/main.css">
    <!-- Link to Fontawesome -->
    <script src="https://use.fontawesome.com/52ae147ef2.js"></script>
  </head>
  <body>
    <header>
      <nav class="navbar">
            <a>
              <img alt="Brand" src="img/Nord_logo.png">
            </a>
            <p class="brand-text">Nord Software</p>
      </nav> <!-- End nav -->
    </header> <!-- End Header -->

    <section class="main-container">
      <section class="page-title">
        <h1>List of partitions</h1>
      </section> <!-- End .page-title -->

      <section class="top-form-container">
        <form class="top-form" action="index.html" method="post">
          <input type="text" name="full-name" value="" placeholder="Full name" class="col-15">
          <input type="email" name="email" placeholder="Email address" class="col-35">
          <input type="number" name="phone-number" value="" placeholder="Phone number" class="col-20">
          <a href="#" class="button-normal col-15">Add New</a>
        </form>
      </section> <!-- End .top-form-container -->



```
2. enterainment_center.py:
```
/* http://meyerweb.com/eric/tools/css/reset/
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
  font-family: 'Roboto', sans-serif;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}

/* ::: General settings ::: */
body {
  background-color: #f1f1f1;
}
p {
  display: inline;
}
/* Universal box-sizing */
html {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*, *:before, *:after {
  -webkit-box-sizing: inherit;
  -moz-box-sizing: inherit;
  box-sizing: inherit;
  }

/* ::: Grid settings ::: */
.col-15 {
  width: 15%;
}
.col-20 {
  width: 20%;
}
.col-35 {
  width: 35%
}



/* ::: Navbar setting ::: */
.navbar {
  display: flex;
  align-items: center;
  padding: 32px;
  background-color: #adb5bd;
}
.brand-text {
  font-size: 1.5em;
  margin-left: 5px;
  letter-spacing: 1px;
  color: white;
}

```

## Getting Started
### Prerequisites
You need to have a code editor like **Atom** or **Sublime**

### Installation
Clone this project (Using `git`command: `git clone https://github.com/vietdang7/HTML5-Test.git` or through your GitDesktop application)

## Testing
1. Open your index.html with your favourite browser 
2. Open project folder in your code editor for editing


## Built With
- HTML5
- CSS3
- Javascript
- jQuery
- CSS Reset from Meyerweb.com

## Unfinished parts
There are unfinised parts in this project due to my limited skills. This should be a React App.

## Contribution
If you want to make contribution for this project, feel free to `fork` this project and make `pull request`

## License

- Copyright of HTML5 Test is belong to [Digiaonline](https://github.com/digiaonline).
- This project is licensed under the MIT license
