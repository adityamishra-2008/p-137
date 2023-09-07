<html>
    <head>
	    <title>Object Finder Web App</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
  
        <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.0.0/p5.js"></script>
  
        <script src="https://unpkg.com/ml5@latest/dist/ml5.min.js"></script>
    
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body background="https://wallpaperaccess.com/full/2024142.jpg">
        <center>
            <h1 class="btn btn-info header">AI Object Finder<br><p>The input name which you will give should match the names present in CoCo model then only it will detect</p></h1>
            <h3 class="object_name_label">Object Name :</h3>
            <input class="input_class" id="input_id">
            <br>
            <button class="btn btn-success" id="start_button_id" onclick="start()">Start</button>
            <br>
            <h3 class="btn btn-danger" id="status"></h3>
            <h3 class="btn btn-warning" id="object_found"></h3>
        </center>
        <script src="main.js"></script>
    </body>
</html>
