<!DOCTYPE html>
<html>
<body>

<h1>The onclick Event</h1>


<button onclick="myFunction()">Click me</button>

<p id="demo"></p>

<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Hello World";
}
</script>

</body>
</html>
