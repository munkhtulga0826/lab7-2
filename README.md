# lab7-2
<html>
<head>
<meta charset="UTF-8" />
<script>
var code
=document.getElementById("password");

var strengthbar= document.getElementById("meter");

code.addEventListener("keyup", function(){checkpassword(code.value)

    })
 var display =document.getElementsByClassName("textbox")[0];
    function checkpassword(password)
    {
    var strength=0;
    if (password.match(/[a-z]+/)){
        strength+=1;
    }
    if (password.match(/[A-Z]+/)){
        strength+=1;
    }
    if (password.match(/[0-9]+/)){
        strength+=1;
    }
    if (password.match(/[$@#&!]+/)){
        strength+=1;

        }
    if (password.length<6){
    display.innerHTML="minimum number of characters is 6":
    }

    if (password.length>12){
            display.innerHTML="maximum number of characters is 12";
}
    switch(strength){
    case 0:
        strengthbar.value=0;
        break;

    case 1:
        strengthbar.value=25;
        break;

    case 2:
        strengthbar.value=50;
        break;

    case 3:
        strengthbar.value=75;
        break;

    case 4:
        strengthbar.value=100;
        break; }
}
</script>
</head>
<body>
</body>
</html>
