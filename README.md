
<html>
<head>
    <style type = "text/css">
          input#id{
              background-color:blue;
              color:white;
              border-reduce:3px;
           }
           p{
              color:red;
           }
    </style>
    <script type = "text/javascript">
           var i = 0;
           function increment(){
                  i++;
                  document.getElementById("d").innerText = i;
           }
    </script>
</head>
<body>
    <p><b><marquee direction = "left">It's My First Web Page</marquee></b></p>
    <input id = "id" type = "button" value = "increment" onclick = "increment();">
    <div id = "d"></div>
</body>
</html>
