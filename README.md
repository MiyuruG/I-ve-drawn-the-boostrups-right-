# html-css-problem
i cant align/change positions in css code 
this is the css code:-

*{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
    font-family: Georgia, 'Times New Roman', Times, serif 

}
.container{
    width: 100%;
}
.container{
    width:80%;
    margin:auto;
}
.row{
    width:80%;
    margin:auto;
}
.container .row .header{
    width: 60%;
    text-align: center;
    margin: auto;


   ----- this is the html code:-----

    <!DOCTYPE html>
<html>
    <head>
        <style>
            body{
                font-family: Verdana, Geneva, Tahoma, sans-serif;
            }
        </style>
        <title>TheBlog</title>
        <meta charset="viewport" content="with=device-with, initial-scale=1.0">
        <meta name="FactM2.0" type="text/css" href="FactM2.0.css">
    </head>
    <body>
           <div class="container">
                <div class="row">
                    <div class="header">
                        <h1>The Blog</h1>
                        <p><h3>-FactMaster-</h3></p>
                    </div>
                    <div class="content">
                        <div class="card">
                            <img src="LK-removebg-preview.png">
                            <h4>find that leter</h4>
                            <p>leter..............wwwwwwwwwwwwwwww............wwwwwwww</p>
                        </div>
                        <div class="card">
                            <img src="LK-removebg-preview.png">
                            <h4>find that leter</h4>
                            <p>leter..............wwwwwwwwwwwwwwww............wwwwwwww</p>
                        </div>
                        <div class="card">
                            <img src="LK-removebg-preview.png">
                            <h4>find that leter</h4>
                            <p>leter..............wwwwwwwwwwwwwwww............wwwwwwww</p>
                        </div>
                    </div>
                </div>
           </div>



    </body>
</html>
}
