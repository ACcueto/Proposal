<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>031921</title>
</head>
<body>
  <h1 id="resultText"></h1>
  <script>
    
    let response = prompt("Can I court you? Type Yes or No");
    let outputText = "";
    
    if (response=="Yes"){
      outputText = "Thank you i will cherish you and youll never regret of saying Yes to me. Hihi!";
    }else if(response=="No"){
      outputText = "I cant accept No as an answer. Hahaha.";
    }else{
      outputText = "please type Yes or No!!";
    }
    
    document.getElementById("resultText").innerHTML = outputText;
  </script>
</body>
</html>
