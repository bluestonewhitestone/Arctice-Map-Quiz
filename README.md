# Arctice-Map-Quiz
Another map quiz 
<!DOCTYPE html>
<html lang="en">
<head>

  <style>
  button {
    position: absolute;
    top: 500px;
    left: 500px;
  }
  img {
    width: 1000px;
    position: absolute;
    z-index: -1;
  }
  #canada{
    position: absolute;
    top: 400px;
    left: 150px;
    width: 47px;
  }
  #display-result{
    position: absolute;
    top: 420px;
    left: 150px;
  }
  #display-result1 {
    position: absolute;
    top: 620px;
    left: 800px;

  }
  #display-result2 {
    position: absolute;
    top: 870px;
    left: 500px;
  }
  #display-result3 {
    position: absolute;
    top: 720px;
    left: 280px;
  }
  #display-result4{
    position: absolute;
    top: 820px;
    left: 370px;
  }
  #display-result5 {
    position: absolute;
    top: 830px;
    left: 620px;
  }
  #display-result6 {
    position: absolute;
    top: 260px;
    left: 310px;
  }
  #display-result7 {
    position: absolute;
    top: 220px;
    left: 410px;
  } 
  #display-result8 {
    position: absolute;
    top: 630px;
    left: 250px;
  }
  #display-result9 {
    position: absolute;
    top: 560px;
    left: 70px;
  }
  #display-result10 {
    position: absolute;
    top: 690px;
    left: 600px;
  }
  #display-result11 {
    position: absolute;
    top: 720px;
    left: 430px;
  }
  #display-result12 {
    position: absolute;
    top: 70px;
    left: 410px;
  }
  #display-result13 {
    position: absolute;
    top: 520px;
    left: 270px;
  }
  #alaska {
    position: absolute;
    top: 240px;
    left: 310px;
    width: 70px;
  }
  #finland {
    position: absolute;
    top: 810px;
    left: 620px;
    width: 70px
  }
  #greenland {
    position: absolute;
    top: 700px;
    left: 280px;
    width: 80px

  }
  #iceland {
    position: absolute;
    top: 800px;
    left: 370px;
    width: 70px;
  }

  #norway {
    position: absolute;
    top: 850px;
    left: 470px;
    width: 100px;
  }
  #russia {
    position: absolute;
    top: 600px;
    left: 800px;
  }
  #beringstrait {
    position: absolute;
    top: 200px;
    left: 410px;
    width: 100px;
  }
  #baffinbay {
    position: absolute;
    top: 610px;
    left: 250px;
    width: 100px;
  }
  #hudsonbay {
    position: absolute;
    top: 540px;
    left: 70px;
    width: 100px;
  }
  #barentssea {
    position: absolute;
    top: 670px;
    left: 600px;
    width: 80px;
  }
  #greenlandsea{
    position: absolute;
    top: 700px;
    left: 430px;
    width: 90px;
  }
  #aleutians {
    position: absolute;
    top: 50px;
    left: 410px;
    width: 80px;
  }
  #queen {
    position: absolute;
    top: 500px;
    left: 270px;
    width: 150px;
  }
  </style>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<input id="canada" type="text">
<button onclick="newFunction();newFunctionOne();newFunctionTwo();newFunctionThree(); newFunctionFour();newFunctionFive();newFunctionSix();newFunctionSeven();newFunctionEight();newFunctionNine();newFunctionTen();newFunctionEleven();newFunctionTwelve();newFunctionThirteen();">Check</button>
<div id="display-result"></div>

<input id="russia" type="text">
<div id="display-result1"></div>


<input id="norway" type="text">
<div id="display-result2"></div>

<input id="greenland" type="text">
<div id="display-result3"></div>

<input id="iceland" type="text">
<div id="display-result4"></div>

<input id="finland" type="text">
<div id="display-result5"></div>

<input id="alaska" type="text">
<div id="display-result6"></div>


<input id="beringstrait" type="text">
<div id="display-result7"></div>

<input id="baffinbay" type="text">
<div id="display-result8"></div>

<input id="hudsonbay" type="text">
<div id="display-result9"></div>

<input id="barentssea" type="text">
<div id="display-result10"></div>

<input id="greenlandsea" type="text">
<div id="display-result11"></div>


<input id="aleutians" type="text">
<div id="display-result12"></div>

<input id="queen" type="text">
<div id="display-result13"></div>


  <script>
  const title = document.createElement("title")
  const head = document.head
const img = document.createElement("img")
const div = document.createElement("div")
const body = document.body
title.innerHTML = "Arctic Quiz"
img.src = "https://upload.wikimedia.org/wikipedia/commons/9/91/Arctic_Ocean_location_map.svg"
body.append(img, div)
head.append(title)

function newFunction(){
if (document.getElementById("canada").value === "Canada" || document.getElementById("canada").value === "canada") {
  document.getElementById("display-result").innerHTML = "correct!"
}
}

function newFunctionOne(){
if (document.getElementById("russia").value === "Russia" || document.getElementById("russia").value === "russia") {
  document.getElementById("display-result1").innerHTML = "correct!"
}
}

function newFunctionTwo(){
if (document.getElementById("norway").value === "Norway" || document.getElementById("norway").value === "norway") {
  document.getElementById("display-result2").innerHTML = "correct!"
}
}


function newFunctionThree(){
if (document.getElementById("greenland").value === "Greenland" || document.getElementById("greenland").value === "greenland") {
  document.getElementById("display-result3").innerHTML = "correct!"
}
}

function newFunctionFour(){
if (document.getElementById("iceland").value === "Iceland" || document.getElementById("iceland").value === "iceland") {
  document.getElementById("display-result4").innerHTML = "correct!"
}
}

function newFunctionFive(){
if (document.getElementById("finland").value === "Finland" || document.getElementById("finland").value === "finland") {
  document.getElementById("display-result5").innerHTML = "correct!"
}
}
function newFunctionSix(){
if (document.getElementById("alaska").value === "Alaska" || document.getElementById("alaska").value === "alaska") {
  document.getElementById("display-result6").innerHTML = "correct!"
}
}

function newFunctionSeven(){
if (document.getElementById("beringstrait").value === "Bering Strait" || document.getElementById("beringstrait").value === "bering strait" || document.getElementById("beringstrait").value === "bering Strait" || document.getElementById("beringstrait").value === "Bering strait" )  {
  document.getElementById("display-result7").innerHTML = "correct!"
}
}
function newFunctionEight(){
if (document.getElementById("baffinbay").value === "baffin bay" || document.getElementById("baffinbay").value === "Baffin Bay" || document.getElementById("baffinbay").value === "Baffin bay" || document.getElementById("baffinbay").value === "baffin Bay" )  {
  document.getElementById("display-result8").innerHTML = "correct!"
}
}

function newFunctionNine(){
if (document.getElementById("hudsonbay").value === "Hudson Bay" || document.getElementById("hudsonbay").value === "Hudson bay" || document.getElementById("hudsonbay").value === "hudson bay" || document.getElementById("hudsonbay").value === "hudson Bay" )  {
  document.getElementById("display-result9").innerHTML = "correct!"
}
}
function newFunctionTen(){
if (document.getElementById("barentssea").value === "barents sea" || document.getElementById("barentssea").value === "Barents Sea" || document.getElementById("barentssea").value === "barents Sea" || document.getElementById("barentssea").value === "Barents sea" )  {
  document.getElementById("display-result10").innerHTML = "correct!"
}
}
function newFunctionEleven(){
if (document.getElementById("greenlandsea").value === "greenland sea" || document.getElementById("greenlandsea").value === "Greenland Sea" || document.getElementById("greenlandsea").value === "greenland Sea" || document.getElementById("greenlandsea").value === "Greenland sea" )  {
  document.getElementById("display-result11").innerHTML = "correct!"
}
}

function newFunctionTwelve(){
if (document.getElementById("aleutians").value === "aleutians" || document.getElementById("aleutians").value === "Aleutians") {
  document.getElementById("display-result12").innerHTML = "correct!"
}
}
function newFunctionThirteen(){
if (document.getElementById("queen").value === "Queen Elizabeth Islands" || document.getElementById("queen").value === "Queen elizabeth islands" || document.getElementById("queen").value === "queen Elizabeth Islands" || document.getElementById("queen").value === "queen elizabeth islands" ||document.getElementById("queen").value === "queen Elizabeth islands" || document.getElementById("queen").value === "Queen Elizabeth islands" ) {
  document.getElementById("display-result13").innerHTML = "correct!"
}
}

function newFunctionFourteen(){
if (document.getElementById("nz").value === "Novaya Zemlya" || document.getElementById("nz").value === "" || document.getElementById("nz").value === "novaya zemlya" || document.getElementById("nz").value === "Novaya zemlya" ||document.getElementById("nz").value === "novaya Zemlya") {
  document.getElementById("display-result14").innerHTML = "correct!"
}
}

</script>
</body>
</html>
