<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Be My Valentine</title>

<style>
body {
  font-family: Arial, sans-serif;
  background: linear-gradient(45deg,#ff4b5c,#ff9a9e);
  color: white;
  text-align: center;
  padding-top: 80px;
}

.container {
  background: white;
  color: black;
  padding: 30px;
  border-radius: 15px;
  width: 300px;
  margin: auto;
}

button {
  padding: 15px 25px;
  font-size: 18px;
  border: none;
  border-radius: 10px;
  cursor: pointer;
}

.yes-button {
  background: hotpink;
  color: white;
}

.no-button {
  background: gray;
  color: white;
}
</style>
</head>

<body>

<div class="container">
  <h2>Will you be my Valentine?</h2>

  <button class="yes-button" onclick="handleYesClick()">Yes</button>
  <button class="no-button" onclick="handleNoClick()">No</button>
</div>

<script>
let messages = [
 "Please 🥺",
 "Think again",
 "Don't do this",
 "Last chance",
 "Okay fine click yes"
];

let messageIndex = 0;

function handleNoClick(){
 const noButton = document.querySelector(".no-button");
 const yesButton = document.querySelector(".yes-button");

 noButton.textContent = messages[messageIndex];
 messageIndex = (messageIndex + 1) % messages.length;

 let currentSize = parseFloat(window.getComputedStyle(yesButton).fontSize);
 yesButton.style.fontSize = (currentSize * 1.5) + "px";
}

function handleYesClick(){
 alert("She said YES ❤️");
}
</script>

</body>
</html>
