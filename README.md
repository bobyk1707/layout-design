# layout-design
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercise - 4</title>
    <style>
        *{
            margin: 0px;
            padding: 0px;
        }
        .container{
            width: 100vw;
            height: 800px;
            background-color: black;
        }
        .header{
            height: 20px;
            background-color: rgb(238, 88, 244);
        }
        .boxes{
            height: 200px;
            width: 95vw;
            display: flex;
            margin: 10px 10px 10px 10px;
            align-self: center;
            padding: 10px;
            justify-content: center;
            background-color: green;
        }
        .box1{
            height: 130px;
            width: 190px;
            margin: 30px 30px 30px 10px;
            padding: 7px;
            background-color: rgb(207, 168, 96);
            border: 1px solid white;
        }
        .box2{
            height: 130px;
            width: 190px;
            margin: 30px 30px 30px 10px;
            padding: 7px;
            background-color: rgb(51, 90, 215);
            border: 1px solid white;
        }
        .content{
            border-radius: 20px;
            height: 90px;
            width: 298px;
            margin-top: 7px;
            margin-left: 619px;
            border: 2px solid white;
            display: flex;
            
            font-size: 20px ;
            text-align: center;
            align-items: center;
            color: white;
            

        }
        .footer{
            
            border: 2px solid rgb(203, 178, 178);
            background-color: rgb(205, 130, 130);
            height: 20px;
            width: 100vw;
            margin: 400px 0px 5px 0px;
            align-items: flex-end;

        }
        img{
            position: fixed;
             border-radius: 50px;
             width: 72px;
             top: 370px;
             right:30px;
        }

    </style>
</head>
<body>
    <div class="container">
        <div class="header"></div>
            <div class="boxes">
                <div class="box1"></div>
                <div class="box2"></div>
            </div>
            
            <div class="content">Welcome to this Sigma Web Development Express</div>
            <div class="icon">
                <img src="SNice.svg.png" >
            </div>
            <div class="footer"></div>
        </div>
    
    
</body>
</html>
