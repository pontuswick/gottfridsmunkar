<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
   <a href="handels.html">Tillbaka (Frontend)</a>
   <h3>backend</h3>
   
   <h1>tack som fan</h1>
   
   
   <h3>kundorder:</h3>
    <p id="textrad"></p>
    <br>
    
    <h3>Munkorder:</h3>
      <p id="textradigen"></p>

   
   <script>
       /*
 var kund = localStorage.getItem("myKund");
        document.getElementById("text").innerHTML=kund;
       */
       /*
       var munk=localStorage.getItem("myDonut");
       document.getElementById("munk").innerHTML=munk;
       */
         var dataBack = JSON.parse(localStorage.getItem("cat"));
document.getElementById("textrad").innerHTML=dataBack;

              var second = JSON.parse(localStorage.getItem("great"));
document.getElementById("textradigen").innerHTML=second;


    </script>
    
</body>
</html>
