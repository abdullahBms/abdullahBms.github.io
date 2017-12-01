
<html>
<head>
    <style type = "text/css">
          table#di{
              color:red;
              border:4px;
              margin_top:4px;
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
                  var H = now.getHours();
                  var M = now.getMinutes();
                  var S = now.getSeconds();
                  var Y = now.getFullYear();
                  var MM = now.getMonth();
                  var D = now.getDate();
                  document.getElementById("di").innerText = H+":"+M+":"+S+<br>+Y+"/"+MM+"/"+D;
           }
           window.setInterval(h,2000);
           var i = 0;
           function increment(){
                  i++;
                  document.getElementById("d").value = i;
           }
    </script>
</head>
<body onload ="h();">
    <h1><b><marquee direction = "left">It's My First Web Page</marquee></b></h1>
    <input id = "id" type = "button" value = "increment" onclick = "increment();">
    <input type = "text" id = "d" readonly = "readonly" value = "0">
    <table id = "di"></table>
</body>
</html>
