# AAcoding02-2-
Homework 
<html lang="en">
<head>
<meta charset="UTF-8">
<link rel="apple-touch-icon" type="image/png" href="https://static.codepen.io/assets/favicon/apple-touch-icon-5ae1a0698dcc2402e9712f7d01ed509a57814f994c660df9f7a952f3060705ee.png" />
<meta name="apple-mobile-web-app-title" content="CodePen">
<link rel="shortcut icon" type="image/x-icon" href="https://static.codepen.io/assets/favicon/favicon-aec34940fbc1a6e787974dcd360f2c6b63348d4b1f4e06c77743096d55480f33.ico" />
<link rel="mask-icon" type="" href="https://static.codepen.io/assets/favicon/logo-pin-8f3771b1072e3c38bd662872f6b673a722f4b3ca2421637d5596661b4e2132cc.svg" color="#111" />
<title>CodePen - AAcoding 02</title>
<style>
.correct {
  background: green;
  
}
.incorrect {
  background: red;
}
</style>
</head>
<body translate="no">
</li><script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<h1> Della's 10 Math Problems </h1>
<ol>
<li> \(2^3\) <input data-correct="8" />
</li>
<li> \( \sqrt [3] {8} \) <input data-correct="2" /></li>
<li> \(\) </li>
</ol>
<script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js'></script>
<script id="rendered-js">
console.clear();

$("input").change(onChange);
function onChange(evt) {
  let correct = $(this).data("correct");
  let response = $(this).val();
  console.log(correct, response);
  if (correct == response) {
    $(this)
      .removeClass("incorrect")
      .addClass("correct");
  } else {
    $(this)
      .removeClass("correct")
      .addClass("incorrect");
  }
}
    </script>
</body>
</html>
