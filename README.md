<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }
        li {
            display: inline-block;
            padding: 10px;
            height: 50px;
            width: 100px;
            font-size: 30px;
            margin: -10px 50px 0 50px;
            transition: all 1s;
        }
        header li:hover {
            background-color: rgb(189, 188, 188);
        }
        a {
            text-decoration: none;
            color: #222;
        }
        #logo {
            float: left;
            padding: 10px;
            font-size: 30px;
            color: blue;
        }
        .header {
            padding: 10px;
            text-align: center;
            height: 50px;
            margin: 0;
            background-color: #222;
        }
        #sideworks {
            width: 200px;
            height: 100%;
            position: fixed;
            margin-left: -10px;
            float: left;
            background-color: #222;
            margin-top: -70px;
        }
        a,strong { animation-duration: 3s; animation-name: rainbowLink; animation-iteration-count: infinite; } 
        @keyframes rainbowLink {     
            0% { color: #ff2a2a; }
            15% { color: #ff7a2a; }
            30% { color: #ffc52a; }
            45% { color: #43ff2a; }
            60% { color: #2a89ff; }
            75% { color: #202082; }
            90% { color: #6b2aff; } 
            100% { color: #e82aff; }
        }
        .list {
            padding: 30px;
            color: white;
            margin: 20px;
            margin-top: 20px;
        }
        #iframe {
            width: 1500px;
            height: 5000px;
        }
    </style>
</head>
<body>
    <header class="header">
        <div id="logo">
            <strong>logo</strong>
        </div>
        <nav>
            <div>
                <ol class="ol">
                    <li><a href="#" style="color: white;">theM</a></li>
                    <li><a href="#" style="color: white;">theM</a></li>
                    <li><a href="#" style="color: white;">theM</a></li>
                    <li><a href="#" style="color: white;">theM</a></li>
                    
                </ol>
            </div>
        </nav>
        <div id="sideworks">
            <div><strong style="font-size: 30px;">logo</strong></div>
            <div>
                <ol>
                    <li class="list"><a href="#">list 1</a></li>
                    <li class="list"><a href="#">list 1</a></li>
                    <li class="list"><a href="#">list 1</a></li>
                    <li class="list"><a href="#">list 1</a></li>
                    <li class="list"><a href="#">list 1</a></li>
                </ol>
            </div>
        </div>
        <article>
            <div>
                <iframe id="iframe" src="http://inseong.gen.hs.kr/main/main.php"></iframe>
            </div>
        </article>
    </header>
    
</body>
</html>
