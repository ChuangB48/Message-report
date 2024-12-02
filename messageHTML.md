# 聊天室HTML程式碼
    <!DOCTYPE html>
    <html>
        <head>
            <title>
                Message
            </title>
            <link href="message.css" type="text/css"    rel="stylesheet"/>
        </head>
        <body>
            <div id="fireboard">
                <img src="firework.png" id="firework">
            </div>
            <span id="title">
                Message(Online:&nbsp;<span id="num"></  span>)
            </span>
            <div id="personal"></div>
            <div id="visibleboard"></div>
            <div id="board"></div>
            <div id="pgdn" onclick="javascript: down()">
                <img src="down.png" id="down">
            </div>
            <input type="text" id="type">
            <div id="send" onclick="javascript: send()">
                send
            </div>
            <div id="detector">
                <div id="photoboard">
                    <img src="photo.png"    id="photosurface">
                    <span id="photospan">photo</span>
                    <input type="file" id="photo"   accept="image/*"  onchange="javascript: light()">
                </div>
                <div id="videoboard">
                    <img src="video.png"    id="videosurface">
                    <span id="videospan">video</span>
                    <input type="file" id="video"   accept="video/*"  onchange="javascript: light()">
                </div>
                <div id="fileboard">
                    <img src="file.png" id="filesurface">
                    <span id="filespan">file</span>
                    <input type="file" id="file"    onchange="javascript: light()">
                </div>
                <div id="other">
                    <span id="add">
                        +
                    </span>
                </div>
            </div>
        </body>
        <script src="message.js"></script>
    </html>

[返回](lobby.md)