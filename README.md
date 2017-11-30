
<html>
<head>
    <style type = "text/css">
          input#id{
              background-color:blue;
              color:white;
              border-radius:3px;
           }
           h1{
              color:red;
           }
           body{
              background-color:lightblue;
           }
           input#d{
              border:3px;
              border-radius:3px;
    </style>
    <script type = "text/javascript">
           var i = 0;
           function increment(){
                  i++;
                  document.getElementById("d").value = i;
           }
    </script>
</head>
<body>
    <marquee direction = "left"><h1><b>It's My First Web Page</b></h1></marquee>
    <input id = "id" type = "button" value = "increment" onclick = "increment();">
    <input type = "text" id = "d" readonly = "readonly" value = "0">
</body>
</html>
