telefonun hecleniyor
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<title>Yükleniyor...</title>
<style>
body{
    margin:0;
    background:#111;
    color:white;
    font-family:Arial,sans-serif;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    text-align:center;
}
#mesaj{
    font-size:32px;
}
</style>
</head>
<body>

<div id="mesaj">
⏳ Yükleniyor...<br><br>
Lütfen bekleyin.
</div>

<script>
setTimeout(function(){
document.getElementById("mesaj").innerHTML =
"😂 <h1>ŞAKA KANKA!</h1><p>Hiçbir şey olmadı. Bu sadece eğlence amaçlıydı.</p>";
},30000);
</script>

</body>
</html>