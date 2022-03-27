<!--Author:Pratigya Panwar -->
<!--Animation HTML file-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animation and keyframe in css</title>
    <style>
        .container{
            background-color: greenyellow;
        }
        .box{
            background-color: green;
            width: 250px;
            height: 250px;
            position: relative;
            animation-name: panwar;
            animation-name: panwar2;
            animation-duration:2s;
            animation-iteration-count: 3;
            /* animation-fill-mode:alternate; */
            /* animation-timing-function: ease-in-out; */
            /* animation-delay: 3s; */
            /* animation-direction: reverse; */
        }
        @keyframes panwar2{
            0%{
                top: 0px;
                left: 0px;

            }
            25%{
                top: 0px;
                left: 250px;

            }
            75%{
                top: 250px;
                left: 250px;
            }
            100%{
                top: 250px;
                left: 0px;

            }
        }
        @keyframes panwar{
            from{
                width: 200px;
                background-color: red;
            }
            to{
                width: 800px;
                background-color: blue;
            }
        }
    </style>
</head>
<body>
    <div class="container">

        <div class="box">
            This is box
        </div>
    </div>
</body>
</html>
