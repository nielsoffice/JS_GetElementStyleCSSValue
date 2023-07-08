# JS_GetElementStyleInlineCSSValue
javaScript / jQuery Get Element style value 

```JS
<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
<script>
$(document).ready(function(){
   
   let colorBackground = $('p').css('backgroundColor');

   console.log( colorBackground );

   // Console Log Result: 
   // rgb(255, 0, 0); which is red;

});
</script>
</head>
<body>

<!-- Getting SCC Property jQuery -->    
<p style="background-color: red;">This is a paragraph.</p>

</body>
</html>

```
