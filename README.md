<!DOCTYPE html>
<html>
<head>
    <style type = "text/css">
          input#id{
              background-color:blue;
              color:white;
           }
    </style>
    <script type = "text/javascript">
           var i = 0;
           function increment(){
                  var in = i++;
                  document.getElementById("d").innerText = in;
           }
    </script>
</head>
<body>
    <p color = "red"><marquee direction = "left"><b>It's My First Web Page</b></marquee></p>
    <input id = "id" type = "button" value = "increment" onclick = "increment();"></input>
    <div id = "d"></div>
</body>
</html>
