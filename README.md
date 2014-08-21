.anime
======

<!doctype html>  
<html lang="en">  
<head>  
  <meta charset="utf-8">  
  <title>animate demo</title>  
  <style>  
  div {  
    background-color: #bca;  
    width: 100px;  
    border: 1px solid green;  
  }  
  </style>  
  <script src="//code.jquery.com/jquery-1.10.2.js"></script>  
</head>  
<body>  
   
<button id="go">&raquo; Run</button>  
<div id="block">Hello!</div>  
   
<script>  
// Using multiple unit types within one animation.  
   
$( "#go" ).click(function() {  
  $( "#block" ).animate({  
    width: "70%",  
    opacity: 0.4,  
    marginLeft: "0.6in",  
    fontSize: "3em",  
    borderWidth: "10px"  
  }, 1000 );  
});  
</script>  
   
</body>  
</html>  
