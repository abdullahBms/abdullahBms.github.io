
<html>
<head>
    <style type = "text/css">
          input#id{
              background-color:blue;
              color:white;
              border-redius:3px;
           }
           p{
              color:red;
           }
           body{
              background-color:lightblue;
           }
           input#d{
              border:3px;
              border-redius:3px;
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
    <h1><b><marquee direction = "left">It's My First Web Page</marquee></b></h1>
    <input id = "id" type = "button" value = "increment" onclick = "increment();">
    <input type = "text" id = "d" readonly = "readonly" value = "0">
</body>
</html>
