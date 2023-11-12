
    <style>
        * {
            margin: 0;
            padding: 0;
            list-style: none;
            font-family: sans-serif;
        }
    
        body {
            background-color: #333;
            text-transform: uppercase;
        }
    
        h1 {
            text-align: center;
        }
    
        h3 {
            margin: 5px;
            border: 1px solid red;
        }
    
        .skils {
            width: 500px;
            margin: 60px auto;
            color: #fff;
            padding: 20px;
            box-shadow: 0 14px 28px rgba(0, 0, 0, 0.25), 0 10px 10px rgba(0, 0, 0, 0.22);
        }
        .skils li{
            margin: 20px 0;
            padding: 10px;
        }
        .bar{
            background: #353b48;
            display: block;
            height: 20px;
            border:1px solid rgba(0,0,0,0.3);
            border-radius:10px;
            overflow: hidden;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
            transition: all 0.3s cubic-bezier(0.25,.8,.25,1);
        }
        .bar:hover{
            box-shadow:0 14px 28px rgba(0, 0, 0, 0.25), 0 10px 10px rgba(0, 0, 0, 0.24);
        }
        .bar span{
            height: 20px;
            float: left;
            background: linear-gradient(135deg,rgba(236,0,140,1)0%, rgba(252,103,103,1)100%);
        }
        .html{
            width: 90%;
            animation: html 3s;
        }
        .css{
            width: 80%;
            animation: css 3s;
        }
        .javascript{
            width: 60%;
            animation: javascript 3s;
        }
        .react{
            width: 10%;
            animation: react 3s;
        }
        @keyframes html{
            0%{
                width:0%;
            }
            100%{
                width: 90%;
            }
        }
        @keyframes css{
            0%{
                width:0%;
            }
            100%{
                width: 80%;
            }
        }
        @keyframes javascript{
            0%{
                width:0%;
            }
            100%{
                width: 60%;
            }
        }
        @keyframes react{
            0%{
                width:0%;
            }
            100%{
                width: 10%;
            }
        }
        
    </style>



<body>
    <div class="skils">
        <h1>My Skils</h1>

        <li>
            <h3>HTML</h3>
            <span class="bar"><span class="html"></span> </span>
        </li>
        <li>
            <h3>CSS</h3>
            <span class="bar"><span class="css"></span> </span>
        </li>
        <li>
            <h3>javascript</h3>
            <span class="bar"><span class="javascript"></span> </span>
        </li>
        <li>
            <h3>React</h3>
            <span class="bar"><span class="react"></span></span>
        </li>
    </div>

</body>

