# 聊天室CSS程式碼
    body{
        overflow: hidden;
        width: 100vw;
        height: 100vh;
        background: radial-gradient(ellipse 90% 110%,   #ebe5d9, #babce3);
    }
    body:hover{
        cursor: default;
    }
    #fireboard{
        position: absolute;
        width: 50px;
        height: 50px;
        top: 0px;
        left: 0px;
        display: flex;
        text-align: center;
        align-items: center;
    }
    #firework{
        position: absolute;
        width: 5px;
        height: 5px;
        left: 50%;
        transform: translateX(-50%);
        opacity: 0;
    }
    #title{
        position: absolute;
        top: 2vh;
        left: 5vw;
        font-size: 5vw;
    }
    #personal{
        position: absolute;
        width: fit-content;
        height: 12vh;
        top: 2vh;
        left: 70vw;
        border: 1px #632A7E solid;
        border-radius: 6vh;
        text-align: center;
    }
    #username{
        font-size: 5vw;
    }
    #visibleboard{
        position: absolute;
        border: 1px #632A7E solid;
        width: 90vw;
        height: 70vh;
        top: 15vh;
        left: 5vw;
        border-radius: 10px;
    }
    #board{
        position: absolute;
        border: transparent;
        width: 90vw;
        height: 65vh;
        top: 15vh;
        left: 5vw;
        border-radius: 10px;
        overflow-x: hidden;
        overflow-y: scroll;
        word-wrap: break-word;
    }
    #pgdn{
        position: absolute;
        border: 1px #632A7E solid;
        width: 5vw;
        height: 5vh;
        top: 80vh;
        left: 90vw;
        border-radius: 10px;
        overflow: hidden;
        text-align: center;
    }
    #pgdn:hover #down{
        transform: rotate(360deg);
    }
    #down{
        width: 3vw;
        height: 5vh;
        transition: all 300ms ease-in-out;
    }
    #type{
        position: absolute;
        width: 30vw;
        height: 2vh;
        top: 90vh;
        left: 5vw;
        background-color: transparent;
        border: 1px #632A7E solid;
        border-radius: 5px;
    }
    #type:focus{
        outline: none;
    }
    #send{
        position: absolute;
        width: 5vw;
        height: 2vh;
        top: 90.1vh;
        left: 35.4vw;
        background-color: transparent;
        border: 1px #632A7E solid;
        border-radius: 5px;
        outline: 1px solid;
        outline-color: #632A7E;
        outline-offset: 0px;
        text-align: center;
        transition: all 200ms ease-out;
    }
    #send:hover{
        outline-color: transparent;
        outline-offset: 15px;
        box-shadow: 0px 0px 5px 0px #632A7E inset;
    }
    #send:active{
        box-shadow: 0px 0px 15px 1px #632A7E inset;
    }
    #detector{
        position: absolute;
        top: 88vh;
        left: 50vw;
        width: 5vw;
        height: 5vw;
        background-color: transparent;
        border: transparent;
        border-radius: 2.5vw;
    }
    #photoboard{
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        left: 0px;
        width: 3vw;
        height: 3vw;
        background-color: transparent;
        border: 1px #fabcaf solid;
        border-radius: 50%;
        overflow: hidden;
        transition: all 300ms ease-in-out;
    }
    #photo{
        position: absolute;
        width: 5vw;
        height: 5vw;
        opacity: 0;
    }
    #photosurface{
        position: absolute;
        top: -26%;
        left: -57%;
        width: 6.2vw;
        height: 4.5vw;
        transition: all 300ms ease-in-out;
    }
    #photospan{
        position: absolute;
        top: 25%;
        left: 10%;
        color: #fabcaf;
        font-size: 1vw;
        opacity: 0;
        transition: all 300ms ease-in-out;
    }
    #videoboard{
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        left: 0px;
        width: 3vw;
        height: 3vw;
        background-color: transparent;
        border: 1px #fabcaf solid;
        border-radius: 50%;
        overflow: hidden;
        transition: all 300ms ease-in-out;
    }
    #video{
        position: absolute;
        width: 5vw;
        height: 5vw;
        opacity: 0;
    }
    #videosurface{
        position: absolute;
        top: -55%;
        left: -77%;
        width: 7vw;
        height: 6vw;
        transition: all 300ms ease-in-out;
    }
    #videospan{
        position: absolute;
        top: 25%;
        left: 10%;
        color: #fabcaf;
        font-size: 1vw;
        opacity: 0;
        transition: all 300ms ease-in-out;
    }
    #fileboard{
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        left: 0px;
        width: 3vw;
        height: 3vw;
        background-color: transparent;
        border: 1px #fabcaf solid;
        border-radius: 50%;
        overflow: hidden;
        transition: all 300ms ease-in-out;
    }
    #file{
        position: absolute;
        width: 5vw;
        height: 5vw;
        opacity: 0;
    }
    #filesurface{
        position: absolute;
        top: -150%;
        left: -207%;
        width: 17vw;
        height: 12.5vw;
        transition: all 300ms ease-in-out;
    }
    #filespan{
        position: absolute;
        top: 25%;
        left: 25%;
        color: #fabcaf;
        font-size: 1vw;
        opacity: 0;
        transition: all 300ms ease-in-out;
    }
    #deletboard{
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        left: 0px;
        width: 3vw;
        height: 3vw;
        background-color: transparent;
        border: 1px #fabcaf solid;
        border-radius: 50%;
        overflow: hidden;
        transition: all 300ms ease-in-out;
    }
    #deletsurface{
        position: absolute;
        top: -118%;
        left: -117%;
        width: 10vw;
        height: 10vw;
        transform: rotate(45deg);
        transition: all 300ms ease-in-out;
    }
    #deletspan{
        position: absolute;
        top: 25%;
        left: 10%;
        color: #fabcaf;
        font-size: 1vw;
        opacity: 0;
        transition: all 300ms ease-in-out;
    }
    #other{
        position: absolute;
        top: 0px;
        left: 0px;
        width: 5vw;
        height: 5vw;
        background-color: red;
        border: 1px red solid;
        border-radius: 50%;
        text-align: center;
        transition: all 300ms;
    }
    #add{
        font-size: 4vw;
    }
    #detector:hover{
        width: 24vw;
    }
    #detector:hover #photoboard{
        left: 8vw;
    }
    #photoboard:hover #photosurface{
        opacity: 0;
    }
    #photoboard:hover #photospan{
        opacity: 1;
    }
    #detector:hover #videoboard{
        left: 14vw;
    }
    #videoboard:hover #videosurface{
        opacity: 0;
    }
    #videoboard:hover #videospan{
        opacity: 1;
    }
    #detector:hover #fileboard{
        left: 20vw;
    }
    #fileboard:hover #filesurface{
        opacity: 0;
    }
    #fileboard:hover #filespan{
        opacity: 1;
    }
    #detector:hover #deletboard{
        left: 26vw;
    }
    #deletboard:hover #deletsurface{
        opacity: 0;
    }
    #deletboard:hover #deletspan{
        opacity: 1;
    }
    #detector:hover #other{
        transform: rotate(45deg);
    }
    .myzone{
        width: 90vw;
        border: transparent;
        height: auto;
        word-wrap: break-word;
        text-align: right;
        overflow: hidden;
    }
    .otherzone{
        width: 90vw;
        border: transparent;
        height: auto;
        word-wrap: break-word;
        text-align: left;
        overflow: hidden;
    }
    .name{
        color: #4BD0D0;
        font-size: 1.5vw;
    }
    .myzone .message{
        position: relative;
        top: auto;
        float: right;
        width: fit-content;
        height: fit-content;
        max-width: 70vw;
        border: 1px #ff00a66b solid;
        border-radius: 20px;
    }
    .otherzone .message{
        position: relative;
        top: auto;
        float: left;
        width: fit-content;
        height: fit-content;
        max-width: 70vw;
        border: 1px #009dff6b solid;
        border-radius: 20px;
    }
    .words{
        font-size: 2vw;
    }
    .photo{
        max-width: 20vw;
        height: auto;
    }
    .control{
        max-width: 20vw;
        height: auto;
    }
    .download{
        width: 5vw;
        height: 7vh;
    }
    .down{
        display: block;
    }
    .time{
        position: relative;
        z-index: -1;
    }
    .time span{
        font-size: 1vw;
    }
    ::-webkit-scrollbar{
        display: none;
    }

[返回](lobby.md)