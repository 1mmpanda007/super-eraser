<!DOCTYPE html>

<html>
    <head>
        <meta charset="utf-8">
        <title>Spin-off of "You're Invited!"</title>
        
        <style>
        body {
            background-image: url("https://www.kasandbox.org/programming-images/seasonal/xmas-ornaments.png");
            background-attachment: fixed;
            background-size: 100%;
            background-repeat: no-repeat;
            font-family: "mistral", cursive;
            text-shadow: 0 0 10px black;
            color: white;
        }
        
        #top-text {
            font-size: 30px;
            text-align: center;
            
        }
        
        #heading {
            color: darkred;
            text-align: center;
            font-family: "mistral", cursive;
            font-size: 80px;
            margin-top: 5px;
            font-weight: normal;
        }
        
        #info {
            margin-top: -10px;
            text-align: center;
            font-size: 27px;
        }
        
        #details {
            text-align: center;
            font-size: 20px;
        }
        
        #break {
            text-align: center;
        }
        
        #rsvp {
            text-align: center;
        }
        a:link, a:visited {
            color: white;
        }
        #disclaimer {
            text-align: center;
        }
        
        </style>
    </head>
    <body>
        <p id="top-text">Please join the  </p>
        <h1 id="heading">Eraser Mark Club!</h1>
        <h2 id="info">It's Erasers again! <br>Please join us to celebrate, and make eraser marks! <br>(Presents are not required.)</h2>
        
        <div id="details">
        <p>Feb,29,2024 • From 6 p.m.</p>
        <p>123 Main Street<br>Wala Wala, Washinton</p>
        </div>
        
        <p id="break">-</p>
        
        <div id="rsvp">
        <p>Identity required</p>
        <form action="demo_form.asp" method="get">
  First name: <input type="text" name="fname"><br>
  Last name: <input type="text" name="lname"><br><br>

</form>
        <button type="button" onclick="alert('Thanks! See you at the party!')">submit</button>
        </div>
        
        
    </body>
</html>
