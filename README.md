<!-- ## Hi there 👋 -->

<!--
**yctCharles/yctCharles** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            padding: 120px;
        }

        .music {
            width: 175px;
            height: 100px;
            display: flex;
        }

        .music span {
            width: 6px;
            border-radius: 18px;
            margin-right: 6px;
        }

        .music span:nth-child(1) {
            /* 时间递增，参差不齐的效果 */
            animation: bar1 2s 0.2s infinite linear;
        }

        .music span:nth-child(2) {
            animation: bar2 2s 0.4s infinite linear;
        }

        .music span:nth-child(3) {
            animation: bar3 2s 0.6s infinite linear;
        }

        .music span:nth-child(4) {
            animation: bar4 2s 0.8s infinite linear;
        }

        .music span:nth-child(5) {
            animation: bar5 2s 1.0s infinite linear;
        }

        .music span:nth-child(6) {
            animation: bar6 2s 1.2s infinite linear;
        }

        .music span:nth-child(7) {
            animation: bar7 2s 1.4s infinite linear;
        }

        .music span:nth-child(8) {
            animation: bar8 2s 1.6s infinite linear;
        }

        .music span:nth-child(9) {
            animation: bar9 2s 1.8s infinite linear;
        }

        @keyframes bar1 {
            0% {
                background: #f677b0;
                margin-top: 25%;
                height: 10%;
            }

            50% {
                background: #f677b0;
                height: 100%;
                margin-top: 0%;
            }

            100% {
                background: #f677b0;
                height: 10%;
                margin-top: 25%;
            }
        }

        @keyframes bar2 {
            0% {
                background: #df7ff2;
                margin-top: 25%;
                height: 10%;
            }

            50% {
                background: #df7ff2;
                height: 100%;
                margin-top: 0%;
            }

            100% {
                background: #df7ff2;
                height: 10%;
                margin-top: 25%;
            }
        }

        @keyframes bar3 {
            0% {
                background: #8c7ff2;
                margin-top: 25%;
                height: 10%;
            }

            50% {
                background: #8c7ff2;
                height: 100%;
                margin-top: 0%;
            }

            100% {
                background: #8c7ff2;
                height: 10%;
                margin-top: 25%;
            }
        }

        @keyframes bar4 {
            0% {
                background: #7fd0f2;
                margin-top: 25%;
                height: 10%;
            }

            50% {
                background: #7fd0f2;
                height: 100%;
                margin-top: 0%;
            }

            100% {
                background: #7fd0f2;
                height: 10%;
                margin-top: 25%;
            }
        }

        @keyframes bar5 {
            0% {
                background: #7ff2d3;
                margin-top: 25%;
                height: 10%;
            }

            50% {
                background: #7ff2d3;
                height: 100%;
                margin-top: 0%;
            }

            100% {
                background: #7ff2d3;
                height: 10%;
                margin-top: 25%;
            }
        }

        @keyframes bar6 {
            0% {
                background: #7ff2a0;
                margin-top: 25%;
                height: 10%;
            }

            50% {
                background: #7ff2a0;
                height: 100%;
                margin-top: 0%;
            }

            100% {
                background: #7ff2a0;
                height: 10%;
                margin-top: 25%;
            }
        }

        @keyframes bar7 {
            0% {
                background: #adf27f;
                margin-top: 25%;
                height: 10%;
            }

            50% {
                background: #adf27f;
                height: 100%;
                margin-top: 0%;
            }

            100% {
                background: #adf27f;
                height: 10%;
                margin-top: 25%;
            }
        }

        @keyframes bar8 {
            0% {
                background: #e7f27f;
                margin-top: 25%;
                height: 10%;
            }

            50% {
                background: #e7f27f;
                height: 100%;
                margin-top: 0%;
            }

            100% {
                background: #e7f27f;
                height: 10%;
                margin-top: 25%;
            }
        }

        @keyframes bar9 {
            0% {
                background: #ecaa64;
                margin-top: 25%;
                height: 10%;
            }

            50% {
                background: #ecaa64;
                height: 100%;
                margin-top: 0%;
            }

            100% {
                background: #ecaa64;
                height: 10%;
                margin-top: 25%;
            }
        }
    </style>
</head>

<body>
    <div class="music">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
    </div>
    <!-- 给每一个bar指定margin-top和height的动画的变化
    为了效果更好看，让每一个bar的背景色都不一样，便是五彩斑斓了 -->
</body>

</html>
