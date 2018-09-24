# plantilla html
<!DOCTYPE html>
<html>
<head>
	<title>rkz9</title>
	<link rel="stylesheet" href="style.css">
	<link rel="javascript" href="lyrics.js">
	<style type="text/css">body, a, a:hover {cursor: url(http://cur.cursors-4u.net/cursors/cur-1/cur48.cur), auto !important;}</style>
	<link href='http://fonts.googleapis.com/css?family=Special Elite' rel='stylesheet' type='text/css'>
	<link href='http://fonts.googleapis.com/css?family=Exo' rel='stylesheet' type='text/css'>
	<link href='http://fonts.googleapis.com/css?family=Wallpoet' rel='stylesheet' type='text/css'>
	<link href="https://fonts.googleapis.com/css?family=VT323" rel="stylesheet">
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/> 
</head>

<body>

<style type="text/css">
body {
    background-color: black;
    font-family: verdana;
    text-align: center;
}
h1{
	color: #FFFFFF;
    font-family: verdana;
    text-align: center;
}
pre{
	color: #FFFFFF;
    font-family: verdana;
    text-align: center;
}
.style75 {
	color: #FF0000;
}

.style74 {
	color: #0B610B;
}
.style73 {
	color: #4C0B5F;
}


</style>



<p> </p>

<script>
TypingText = function(element, interval, cursor, finishedCallback) {
if((typeof document.getElementById == "undefined") || (typeof element.innerHTML ==

"undefined")) {
this.running = true;
return;
}
this.element = element;
this.finishedCallback = (finishedCallback ? finishedCallback : function() { return; });
this.interval = (typeof interval == "undefined" ? 100 : interval);
this.origText = this.element.innerHTML;
this.unparsedOrigText = this.origText;
this.cursor = (cursor ? cursor : "");
this.currentText = "";
this.currentChar = 0;
this.element.typingText = this;
if(this.element.id == "") this.element.id = "typingtext" + TypingText.currentIndex++;
TypingText.all.push(this);
this.running = false;
this.inTag = false;
this.tagBuffer = "";
this.inHTMLEntity = false;
this.HTMLEntityBuffer = "";
}
TypingText.all = new Array();
TypingText.currentIndex = 0;
TypingText.runAll = function() {
for(var i = 0; i < TypingText.all.length; i++) TypingText.all[i].run();
}
TypingText.prototype.run = function() {
if(this.running) return;
if(typeof this.origText == "undefined") {
setTimeout("document.getElementById('" + this.element.id + "').typingText.run()",

this.interval); // We haven't finished loading yet. Have patience.
return;
}
if(this.currentText == "") this.element.innerHTML = "";
// this.origText = this.origText.replace(/<([^<])*>/, ""); // Strip HTML from text.
if(this.currentChar < this.origText.length) {
if(this.origText.charAt(this.currentChar) == "<" && !this.inTag) {
this.tagBuffer = "<";
this.inTag = true;
this.currentChar++;
this.run();
return;
} else if(this.origText.charAt(this.currentChar) == ">" && this.inTag) {
this.tagBuffer += ">";
this.inTag = false;
this.currentText += this.tagBuffer;
this.currentChar++;
this.run();
return;
} else if(this.inTag) {
this.tagBuffer += this.origText.charAt(this.currentChar);
this.currentChar++;
this.run();
return;
} else if(this.origText.charAt(this.currentChar) == "&" && !this.inHTMLEntity) {
this.HTMLEntityBuffer = "&";
this.inHTMLEntity = true;
this.currentChar++;
this.run();
return;
} else if(this.origText.charAt(this.currentChar) == ";" && this.inHTMLEntity) {
this.HTMLEntityBuffer += ";";
this.inHTMLEntity = false;
this.currentText += this.HTMLEntityBuffer;
this.currentChar++;
this.run();
return;
} else if(this.inHTMLEntity) {
this.HTMLEntityBuffer += this.origText.charAt(this.currentChar);
this.currentChar++;
this.run();
return;
} else {
this.currentText += this.origText.charAt(this.currentChar);
}
this.element.innerHTML = this.currentText;
this.element.innerHTML += (this.currentChar < this.origText.length - 1 ? (typeof
this.cursor == "function" ? this.cursor(this.currentText) : this.cursor) : "");
this.currentChar++;
setTimeout("document.getElementById('" + this.element.id + "').typingText.run()",
this.interval);
} else {
this.currentText = "";
this.currentChar = 0;
this.running = false;
this.finishedCallback();
}
}
</script>


<div id="example1"></div>

<span class="luz" id="blink"><h1 id="example2">rkz9</h1></span>


<script type="text/javascript">
//Define first typing example:
new TypingText(document.getElementById("example1"));
//Define second typing example (use "slashing" cursor at the end):
new TypingText(document.getElementById("example2"), 40, function(i){ /*velocidad de cusor en 40 por defecto*/
var ar = new Array("_","_","_","_"); return " " + ar[i.length %
ar.length]; });
//Type out examples:
TypingText.runAll();
</script>
<script>
(function() {

setInterval(function(){
  var el = document.getElementById('blink');
  if(el.className == 'luz'){
      el.className = 'luz on';
  }else{
      el.className = 'luz';
  }
},500);

})();
</script>

<style>
.luz.on{
  color: #FF0000;/*color del texto al cambiar*/
  text-shadow:
     1px  1px rgba(255, 255, 255, .1),
    -1px -1px rgba(0, 0, 0, .88),
     0px  0px 20px #FF0000;/*color de la luz del texto*/
}
.luz{
  color: #FFFFFF;
  text-shadow:
     1px  1px rgba(255, 255, 255, .1),
    -1px -1px rgba(0, 0, 0, .88);
}
</style>

</script>
<script type="text/javascript">
writeContent(true);
</script>
<p> </p>

<div id="example5"></div>
<pre id="example6">
<strong>My instagram: <span class="style75">@_rkz9.</span>
   <span class="style75">Mi web: </span>rkz9.tk.</span>
   <span class="style73">-GhostSquad</span></strong>
</pre>

 



<script type="text/javascript">
//Define first typing example:
new TypingText(document.getElementById("example5"));
//Define second typing example (use "slashing" cursor at the end):
new TypingText(document.getElementById("example6"), 40, function(i){ /*velocidad de cusor en 40 por defecto*/
var ar = new Array("_","_","_","_"); return " " + ar[i.length %
ar.length]; });
//Type out examples:
TypingText.runAll();
</script>
<img src="eldan.jpg" height="300"  border="0" border="0">
<div id="player">
    <audio autoplay hidden>
     <source src="song.mp3" type="audio/mp3">
    </audio>
</div>

</span></strong><br>
</body>
</html>
