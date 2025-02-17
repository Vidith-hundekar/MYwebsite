<!DOCTYPE html>
<html>
    <head>
        <title>Vidith's homepage</title>
        <link rel="stylesheet" href="webstyle.css">
        <script>
            document.getElementById("img1").addEventListener("mouseover",function(){
                document.getElementById("img1").style.filter="blur(500px)";
            });
            </script>
    </head>
    <body >
        <header>
            <p >Homepage</p>
        </header>
        <nav>
            <a href="http://127.0.0.1:3000/webhome.html">Home</a>
            <a href="http://127.0.0.1:3000/webhobbies.html">Hobbies</a>
            <a href="http://127.0.0.1:3000/webacheiv.html">Achievements</a>
            <a href="http://127.0.0.1:3000/webcontact.html">Contact me</a>
        </nav>
        <br>
        <div class="box" style="text-align: center; font-size: 25px;">
            <img id="img1" src="krishna.jpeg" width=250 margin-left="20px" align="center">
            --VIDITH
        </div >
        <p style="padding:  20px; text-align: center; background-color: blanchedalmond; margin-top: 100px; font-size: 30px; position: relative; left:40px ">Height  : somewhere between(5'5 to 5'6) <br>Weight:51kg-wt </p>
</html>
