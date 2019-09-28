<!DOCTYPE html>
<html lang="en">
<head>
    <title>Media Query Basic</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /*화면 넓이 0~767*/
        @media screen and (max-width: 767px) {
            html {
                background: red;
                color: white; font-weight: bold
            }
        }
        /*화면 넓이 768~959*/
        @media screen and (min-width: 768px) and (max-width: 959px) {
            html {
                background: green;
                color: white; font-weight: bold;
            }
        }
        /*화면 넓이 960~무한*/
        @media screen and (min-width: 960px) {
            html {
                background: blue;
                color: white; font-weight: bold;
            }
        }
    </style>
</head>
<body>
    <h1>lorem ipsum</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta optio dolor sequi, id consequatur porro, hic nostrum dignissimos eum corrupti vel consectetur suscipit architecto! Soluta quos dicta cum magnam aspernatur.</p>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Mollitia recusandae neque rerum facilis, amet repudiandae vitae eligendi, commodi omnis, atque exercitationem soluta eaque. Ipsam eligendi rem, quia repudiandae at consectetur?</p>
</body>
</html>
