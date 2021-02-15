<!DOCTYPE html>
<html>

<head>
    <title>New tab</title>
</head>

<style>
html, body {margin: 0;
height: 100%;}

#nav {display: flex;
justify-content: flex-end;
margin-top: 15px;}

#nav a {margin-right: 20px;}

#nav a.topimage {width: 20px;
height: 20px;
background: darkorange;
border-radius: 50px;}

#middle {flex-grow: 1;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;}

#logo{text-align: center;}

#searchbarcontainer {margin-top: 20px;text-align: center;}

#searchbar {padding-top: 10px;
padding-bottom: 10px;
outline: 0;
width: 500px;
border-radius: 15px;
border: 1px solid #c4c4c4;}

#buttons {margin-top: 20px;
display: flex;
justify-content: center;}

.button {margin-left: 10px;
margin-right: 10px;
padding: 5px 10px;
cursor: pointer;
border-radius: 3px;
background: rgb(231,231,231);}

#links {margin-top: 20px;
text-align: center}

body {display: flex;
flex-direction: column;}

#footer {}
</style>

<body>
     <div id="nav">
     <a class="toplink">Gmail</a>
     <a class="toplink">Attēli</a>
     <a class="topimage"></a>
     </div>

<div id="middle">

<div id="logo">
<img src="https://www.google.lv/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png">
</div>

<div id="searchbarcontainer">
<input id="searchbar"
type=text>

</div>

<div id="buttons">
<div class="button">
Google meklēšana
</div>
<div class="button">
Es ticu veiksmei!
</div>
</div>

<div id="links">
Google piedāvājums:
<a href="">English</a>
<a href="">lietuvių</a>
<a href="">русский</a>
</div>
</div>



<div id="footer">
<div id="footer-contetnt">
Latvija
</div>
</div>
</body>

</html>