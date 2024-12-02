# 登入畫面CSS程式碼
    body{
        overflow: hidden;
        width: 100vw;
        height: 100vh;
        background: radial-gradient(ellipse 90% 110%,   #ebe5d9, #babce3);
    }
    body:hover{
        cursor: default;
    }
    span{
        color: #632A7E;
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
    #empty{
        position: absolute;
        outline: 1px solid;
        outline-color: #fabcaf;
        top: 0px;
        left: 0px;
        background-color: #fabcaf;
        width: 100vw;
        height: 15vh;
        text-align: center;
        opacity: 0;
    }
    #alert{
        color: red !important;
        font-size: 10vh;
    }
    #login{
        position: fixed;
        border: 1px #632A7E solid;
        width: 50vw;
        height: 50vh;
        left: 25vw;
        top: 20vh;
        border-radius: 10px;
        text-align: center;
    }
    #caption{
        width: auto;
        height: auto;
        font-size: 7vh;
    }
    #username{
        width: 15vw;
        height: auto;
        background-color: transparent;
        border: 1px #632A7E solid;
        border-radius: 5px;
        transition: all 300ms ease-in-out;
    }
    #username:focus{
        box-shadow: 0px 0px 1000px 70px #4bd0d05c;
        outline: none;
    }
    #bg{
        position: absolute;
        top: 0px;
        left: 0px;
        background-color: #fabcaf;
        width: 5vh;
        height: 5vh;
        border-radius: 2.5vh;
        transition: all 300ms ease-in-out;
    }
    #word{
        position: absolute;
        top: 0px;
        left: 4vw;
        font-size: 4vh;
    }
    #arrow{
        position: absolute;
        top: 1.5vh;
        left: 9vw;
        width: 4vh;
        height: 2vh;
        transition: all 300ms ease;
    }
    #start{
        position: absolute;
        left: 17.5vw;
        width: 15vw;
        height: 5vh;
        background-color: transparent;
        border-radius: 2.5vh;
        border: transparent;
        overflow: hidden;
    }
    #start:hover #bg{
        width: 15vw;
    }
    #start:hover #arrow{
        left: 10vw;
    }

[返回](lobby.md)