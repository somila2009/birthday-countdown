<html>
<head>
<body>
<body bgcolor="lightpink">
<h1>Why did i make it</h1> 
<p>hi everyone thank you for joing/entering my project that i put my heart and soul into !!!</p>
<hr size="5" width="100%" color="black"/>
<h1>Birthday's</h1>
 <p>Tata:20 July
    <h2 id="timer1"></h2>
  </p>

  <p>Mama:14 August
    <h2 id="timer15"></h2>
    <p>Ma Bre:26 August<h2 id="timer9"></h2>
  </p>
  </p>
  <p>Ovayo:25 November <h2 id="timer3"></h2>
  </p>
  <p>Somila:08 Febuary<h2 id="timer4"></h2>
  </p>
  <p>Uminathi:24 August<h2 id="timer5"></h2>
  </p>
  <p>Usiphile:22 Decmber<h2 id="timer6"></h2>
  </p>
  <p>Linothando:03 October<h2 id="timer7"></h2>
  </p>
  <p>Olunje:09 October<h2 id="timer8"></h2>
  </p>
  <script>

  // Tata's countdown
let countDownDate1 = new Date("Jul 20, 2025 00:00:00").getTime();
let countdown1 = setInterval(function() {
  let now = new Date().getTime();
  let distance = countDownDate1 - now;

  let days = Math.floor(distance / (1000 * 60 * 60 * 24));
  let hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  let minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  let seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("timer1").innerHTML =
    days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(countdown1);
    document.getElementById("timer1").innerHTML = "IT'S TIME! 🎊";
  }
}, 1000);

// Mama's countdown
let countDownDate15 = new Date("aug 14, 2025 00:00:00").getTime();
let countdown15 = setInterval(function() {
  let now = new Date().getTime();
  let distance = countDownDate15 - now;

  let days = Math.floor(distance / (1000 * 60 * 60 * 24));
  let hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  let minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  let seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("timer15").innerHTML =
    days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(countdown2);
    document.getElementById("timer15").innerHTML = "IT'S TIME! 🎊";
  }
}, 1000); 

// Ovayo's countdown
let countDownDate3 = new Date("Nov 25, 2025 00:00:00").getTime();
let countdown3 = setInterval(function() {
  let now = new Date().getTime();
  let distance = countDownDate3 - now;

  let days = Math.floor(distance / (1000 * 60 * 60 * 24));
  let hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  let minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  let seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("timer3").innerHTML =
    days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(countdown2);
    document.getElementById("timer3").innerHTML = "IT'S TIME! 🎊";
  }
}, 1000); 

// Somila's countdown
let countDownDate4 = new Date("Feb 08, 2026 00:00:00").getTime();
let countdown4 = setInterval(function() {
  let now = new Date().getTime();
  let distance = countDownDate4 - now;

  let days = Math.floor(distance / (1000 * 60 * 60 * 24));
  let hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  let minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  let seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("timer4").innerHTML =
    days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(countdown2);
    document.getElementById("timer4").innerHTML = "IT'S TIME! 🎊";
  }
}, 1000); 

// Uminathi's countdown
let countDownDate5 = new Date("Aug 24, 2025 00:00:00").getTime();
let countdown5 = setInterval(function() {
  let now = new Date().getTime();
  let distance = countDownDate5 - now;

  let days = Math.floor(distance / (1000 * 60 * 60 * 24));
  let hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  let minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  let seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("timer5").innerHTML =
    days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(countdown2);
    document.getElementById("timer5").innerHTML = "IT'S TIME! 🎊";
  }
}, 1000); 

// Usiphile's countdown
let countDownDate6 = new Date("Dec 22, 2025 00:00:00").getTime();
let countdown6 = setInterval(function() {
  let now = new Date().getTime();
  let distance = countDownDate6 - now;

  let days = Math.floor(distance / (1000 * 60 * 60 * 24));
  let hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  let minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  let seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("timer6").innerHTML =
    days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(countdown6);
    document.getElementById("timer6").innerHTML = "IT'S TIME! 🎊";
  }
}, 1000); 
  
  // Linothando's countdown
  let countDownDate7 = new Date("Oct 07, 2025 00:00:00").getTime();
let countdown7 = setInterval(function() {
  let now = new Date().getTime();
  let distance = countDownDate7 - now;

  let days = Math.floor(distance / (1000 * 60 * 60 * 24));
  let hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  let minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  let seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("timer7").innerHTML =
    days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(countdown9);
    document.getElementById("timer7").innerHTML = "IT'S TIME! 🎊";
  }
}, 1000);

 // 0lunje's countdown
  let countDownDate8 = new Date("Oct 09, 2025 00:00:00").getTime();
let countdown8 = setInterval(function() {
  let now = new Date().getTime();
  let distance = countDownDate8 - now;

  let days = Math.floor(distance / (1000 * 60 * 60 * 24));
  let hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  let minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  let seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("timer8").innerHTML =
    days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(countdown9);
    document.getElementById("timer8").innerHTML = "IT'S TIME! 🎊";
  }
}, 1000);

// Ma Bre's countdown
  let countDownDate9 = new Date("Aug 26, 2025 00:00:00").getTime();
let countdown9 = setInterval(function() {
  let now = new Date().getTime();
  let distance = countDownDate9 - now;

  let days = Math.floor(distance / (1000 * 60 * 60 * 24));
  let hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  let minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  let seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("timer9").innerHTML =
    days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(countdown9);
    document.getElementById("timer8").innerHTML = "IT'S TIME! 🎊";
  }
}, 1000);
</script>
<hr size="5" width="100%" color="black">
<p>thank you for taking a look at my webpage </p>
</body>
