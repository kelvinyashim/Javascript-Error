# Javascript-Error
<!DOCTYPE>
<html>
<body>

<input id="demo" name="x" type="text">
<button type="button" onclick="checkNum()"> Check Num </button>
<p id="demo1"></p
<script>
function checkNum(){
var error, x;
error= document.getElementById("demo1");
error.innerHTML=" ";
x = document.getElementById("demo").value;
try{
if (x== "") "throw empty";
if (isNaN(x)) "throw not a number";
x = Number(x);
if (x < 5) "throw too low";
if (x > 10 ) "throw too high";
)
catch(err){
error.innerHTML+= " " + err;}
}
</script>



</body>


</html>
