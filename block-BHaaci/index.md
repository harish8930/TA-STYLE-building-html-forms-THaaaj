
  <!DOCTYPE html>
  <html lang="en">
  
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
  </head>
  
  <body>
  <header>
<form action="index.html" method="post"  >

  <fieldset>


<input type="text" id="name" placeholder="Your Name">


<input type="text" id="name" placeholder="Last Name">


<input type="email" id="name" placeholder="Email Address"         >


<input type="password" id="name" placeholder="Password"  >

<button>Claim your free trail</button>


  </fieldset>

</form>
<button class="btn">Try it for free then 20$/month </button>

<div class="sidebar">
<h2>Learn to code by watching others</h2>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus commodi maiores eos labore doloremque quos rerum sint alias voluptatibus, deleniti explicabo numquam.
</p>
</div>
</body>
</html>
  
  style.css
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
	border-spacing: 0; }

/*starts here*/

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
	border-collapse: collapse;}



	/*start*/
@font-face{font-family: "open sans regular"; src: url(OpenSans-VariableFont_wdth\,wght.ttf);}
body{font-family:"open sans regular";}

*,
*::before,
*::after{box-sizing: border-box;}

form{max-width: 300px;
margin-left: 800px;
position: absolute;
top: 80px;
}

input{margin:20px 20px;
height: 35px;
width: 250px;
}
fieldset{background-color: rgb(255, 252, 252);
width: 300px;
border-radius: 8px;
height: 360px;
}

::placeholder{
height: 50px;
font-family:"open sans regular";
}


header{background-image: url(bg-intro-desktop.png);
max-width: 1350px;
height: 500px;
background-color: rgb(245, 97, 122);
margin: 0 auto;
}
button{background-color: rgb(69, 207, 69);
width: 250px;
height: 35px;
border: 0px;
color: white;
margin-left: 20px;
margin-bottom: 10px;
border-radius: 4px;

}
.sidebar{width: 400px;
padding-top: 70px;
margin-left: 230px;
}

h2{font-size: 30px; 
color: white;
}
p{font-size: 16px;
color: white;
line-height: 1.3;
}
.btn{background-color: rgb(86, 15, 153);
	width: 300px;
	height: 35px;
	border: 0px;
	color: white;
	margin-left: 20px;
	margin-bottom: 20px;
	border-radius: 4px;
margin-left: 800px;
margin-top:30px;
text-align: center;
}
  
  
  
  
  
  
  
  
  
