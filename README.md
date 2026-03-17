# Web-Development-HTML-CSS-JS-
<!DOCTYPE html>
<html>
<head>
<title>Basic Webpage</title>

<style>
body {
  font-family: Arial;
  background-color: lightgray;
  text-align: center;
}

h1 {
  color: darkgreen;
}

button {
  padding: 10px;
  background-color: green;
  color: white;
}
</style>

</head>
<body>

<h1>Basics of Web Development</h1>

<p>This webpage uses HTML, CSS, and JavaScript.</p>

<img src="https://as1.ftcdn.net/v2/jpg/02/14/53/92/1000_F_214539232_YnUrtuwUEt84gHuU0qG8l7OwZvH4rnPG.jpg" alt="web Development">

<br><br>

<a href="https://www.Codecademy.com">Visiting the Codecademy</a>

<br><br>

<button onclick="showAlert()">Click Me</button>

<script>
function showAlert() {
  alert("Hello! You clicked the button.");
}
</script>

</body>
</html>
