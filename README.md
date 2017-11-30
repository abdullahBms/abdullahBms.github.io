
<html>
<head>
    <style type = "text/css">
          div#di{
              background-color:yellow;
              color:red;
           }
          input#id{
              background-color:blue;
              color:white;
              border-radius:3px;
           }
           h1{
              color:red;
           }
           body{
              background-color:lightgreen;
           }
           input#d{
              border:3px;
              border-radius:3px;
    </style>
    <script type = "text/javascript">
           function h(){
                  var now = new Date();
                  var hh = now.getHours();
                  var mm = now.getMinuyes();
                  var ss = now.getSeconds();
                  document.getElementById("di").innerText = now;
           }
           var i = 0;
           function increment(){
                  i++;
                  document.getElementById("d").value = i;
           }
    </script>
</head>
<body onload = "h();">
    <h1><b><marquee direction = "left">It's My First Web Page</marquee></b></h1>
    <input id = "id" type = "button" value = "increment" onclick = "increment();">
    <input type = "text" id = "d" readonly = "readonly" value = "0">
    <div id = "di"></div>
</body>
</html>
