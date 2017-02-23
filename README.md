
<!DOCTYPE html>
<html>
<title>Tabs</title>
<head>
<style>
.link{
    text-decoration: none;
    text-align: center;
    float: left;
	margin-top:15px;
	margin-left:10px;
	padding-right:15px;
    display: block;
    color: black;
    font-size: 15px;
}
.tabs{
	height: 50px;
    background:gray;
}
.tabs a:hover{
color:whitesmoke;
}
.content{
    width: 50%;
    height: 100px;
    background-color: gainsboro;
	display:none;
}

</style>
</head>
<body>
	<div class="tabs">
		<a href="#" class="link" onclick= "openTab()">Phani</a>
		<a href="#" class="link" onclick= "openTab1()">Krishna</a>
		<a href="#" class="link" onclick= "openTab2()">kishon</a>
		<a href="#" class="link" onclick= "openTab3()">PC</a>
		<a href="#" class="link" onclick= "openTab4()">vijay</a>
		<a href="#" class="link" onclick= "openTab5()">Rajith</a>
	</div>
<div id="phani" class="content">
  <h3>Name:Phani</h3>
  <p>College:Swarnandra college of engineering and technology.</p>
  <p>From:Guntur</P>
</div>

<div id="krishna" class="content">
  <h3>Name:Krishna</h3>
  <p>College:Swarnandra college of engineering and technology.</p>
  <p>From:kikalur</P>
</div>

<div id="Kishon" class="content">
  <h3>Name:kishon</h3>
  <p>College:North west Mossouri state University.</p>
  <p>From:USA
</div>
<div id="pc" class="content">
  <h3>Name:PC</h3>
  <p>College:Swarnandra college of engineering and technology.</p>
  <p>From:Vijayawada</P>
</div>

<div id="vijay" class="content">
  <h3>Name:Vijay</h3>
  <p>College:Swarnandra college of engineering and technology.</p>
  <p>From:Rajamundhry</P>
</div>

<div id="Rajith" class="content">
  <h3>Name:Rajith</h3>
  <p>College:University of Texas.</p>
  <p>From:USA
</div>
<script>
function openTab(){
document.getElementById('phani').style='display:block';
document.getElementById('krishna').style='display:none';
document.getElementById('Kishon').style='display:none';
document.getElementById('pc').style='display:none';
document.getElementById('vijay').style='display:none';
document.getElementById('Rajith').style='display:none';
}

function openTab1(){
document.getElementById('krishna').style='display:block';
document.getElementById('phani').style='display:none';
document.getElementById('Kishon').style='display:none';
document.getElementById('pc').style='display:none';
document.getElementById('vijay').style='display:none';
document.getElementById('Rajith').style='display:none';
}
function openTab2(){
document.getElementById('Kishon').style='display:block';
document.getElementById('pc').style='display:none';
document.getElementById('vijay').style='display:none';
document.getElementById('Rajith').style='display:none';
document.getElementById('phani').style='display:none';
document.getElementById('krishna').style='display:none';
}
function openTab3(){
document.getElementById('phani').style='display:none';
document.getElementById('krishna').style='display:none';
document.getElementById('Kishon').style='display:none';
document.getElementById('pc').style='display:block';
document.getElementById('vijay').style='display:none';
document.getElementById('Rajith').style='display:none';
}
function openTab4(){
document.getElementById('phani').style='display:none';
document.getElementById('krishna').style='display:none';
document.getElementById('Kishon').style='display:none';
document.getElementById('pc').style='display:none';
document.getElementById('vijay').style='display:block';
document.getElementById('Rajith').style='display:none';
}
function openTab5(){
document.getElementById('phani').style='display:none';
document.getElementById('krishna').style='display:none';
document.getElementById('Kishon').style='display:none';
document.getElementById('pc').style='display:none';
document.getElementById('vijay').style='display:none';
document.getElementById('Rajith').style='display:block';
}

</script>

</body>
</html>
