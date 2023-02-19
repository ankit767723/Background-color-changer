# Background-color-changer

<!DOCTYPE html>
<html>
    <head>
        <meta charset = "utf-8"/>
        <meta name="viewport" content="width-device-width, initial-scale-1.0">
        <title>Javascript exercise </title>
    </head>
    <body>
        <script>
            var bgcolor = new Array ("#029FD4","#D43702","#EAEAFF","#FFEAOO","#AB5252","#FFFFFF","#DE28D8")
            document.body.style.background = bgcolor[Math.floor(Math.random()*bgcolor.length)]
        </script>
    </body>
</html>
