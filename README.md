html {
    line-height: 1.15; /* 1 */
    -webkit-text-size-adjust: 100%; /* 2 */
}

body {
    font-size: 16px;
    font-family: "Arial", Helvetica, sans-serif;
    margin: 0;
    color: #000;
}

main { 
    display: block;
    padding: 30px 0;
}

* { outline: none !important; }

a:hover {
    text-decoration: none;
    opacity: 0.95;
}

h1, h2, h3, h4, h5, h6, p, a, input, div, textarea, label {
    margin: 0;
}

h2 { font-size: 28px; }

ul {
    list-style: none;
    padding-left: 0;
    font-weight: 400;
    font-style: normal;
    margin: 0;
}

p { font-size: 1em; }

img { border-style: none; }

.container {
    width: 1200px;
    margin: 0 auto;
    padding: 0 15px;
    max-width: 100%;
    box-sizing: border-box;
}

.clearfix::after {
    content: "";
    clear: both;
    display: table;
}

/* End General Settings */

/* Header */

header { 
    background: Sienna; 
    padding: 10px;
}

.title-header .title {
    display: inline-block;
    color: #fff;
    font-size: 18px;
}

.title-header .logo {
    display: inline-block;
}

.title-header .logo img {
    vertical-align: middle;
}

nav { background: #262d33; }

nav li a { 
    color: #AFB2B6;
    display: inline-block;
    padding: 10px 10px;
}

/* End Header */

/* Footer */

footer {
    background: #333;
    color: #fff;
    padding: 10px;  
    height: 100px;
}

footer a { color: cornsilk; }

/* End Footer */

/* Home Page Content */

.menu-item.additional-items h2 {
    width: 50%;
    float: left;
}

.menu-item.additional-items .item-inner ul {
    display: inline-block;
    width: 50%;
    float: left;
}

/* End Home Page Content */

/* Page Content */

.event-item {
    margin-bottom: 25px;
    border: 1px solid #000
}

