# 登入畫面HTML程式碼
    <!DOCTYPE html>
    <html>
        <head>
            <title>
                Login
            </title>
            <link href="login.css" type="text/css"  rel="stylesheet"/>
        </head>
        <body>
            <div id="fireboard">
                <img src="firework.png" id="firework">
            </div>
            <div id="empty">
                <span id="alert">
                    Username can't be empty!
                </span>
            </div>
            <div id="login">
                <br><br><br><br>
                <span id="caption">
                    Enter Your Username
                </span>
                <br><br><br><br><br><br>
                <input type="text" id="username">
                <br><br><br>
                <div id="start" onclick="javascript: start  ()">
                    <div id="bg"></div>
                    <span id="word">
                        start
                    </span>
                    <img src="arrow.png" id="arrow">
                </div>
            </div>
        </body>
        <script src="login.js"></script>
    </html>

[返回](lobby.md)