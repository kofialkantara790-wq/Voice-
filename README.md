# Voice-
Umsonst
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>AI Voice Pro</title>
<style>
body {
  background: linear-gradient(135deg,#0f172a,#1e293b);
  color: white;
  font-family: Arial;
  text-align: center;
}
.container {
  margin-top: 50px;
}
textarea, input {
  width: 300px;
  padding: 10px;
  margin: 10px;
  border-radius: 10px;
  border: none;
}
button {
  background: #22c55e;
  border: none;
  padding: 12px 25px;
  border-radius: 12px;
  color: white;
  cursor: pointer;
}
</style>
</head>

<body>

<div class="container">
  <h1>🎙️ AI Voice Pro</h1>
  <p>استنساخ الصوت بشكل احترافي</p>

  <input type="file" id="audio"><br>
  <textarea id="text" placeholder="اكتب النص"></textarea><br>

  <button onclick="generate()">🎧 توليد الصوت</button>

  <p id="status"></p>
</div>

<script>
function generate() {
  document.getElementById("status").innerText =
  "🚀 يتم المعالجة... (يحتاج ربط AI)";
}
</script>

</body>
</html>
