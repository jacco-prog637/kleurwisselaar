<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <title>Kleurwisselaar</title>

   <style>
     body {
            background-color: white;
            text-align: center;
            margin-top: 100px;
            font-family: Arial, sans-serif;
     }

        button {
            padding: 15px 30px;
            font-size: 18px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
    }

     button:hover {
          background-color: #45a049;
     }
    <style>
</head>
<body>

     <h1>interactive kleurwisselaar</h1>

    <button onclick="veranderKleur()">Verander Kleur</button>

    <script>
    function veranderKleur() {
        var kleuren = ['red', 'blue', 'green', 'yellow', 'pink', 'purple', 'orange'];
        var randomKleur = kleuren[Math.floor(Math.random() * kleuren.length)];
        document.body.style.backgroundColor = randomKleur;
        document.body.style.color = 'white';
        alert("JavaScript werkt!");

    }
</script>


</body>
</html>
        

        
