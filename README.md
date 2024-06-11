<html>
    <head>
        <meta charset="utf-8">
        <title>A.R.C. books</title>
        <style>
            #page{
                text-align: center;
            }
            #book{
                overflow: auto;
                width: 100%;
                height: 450px;
            }
            button{
                background:green;
            }
            #books{
                overflow: auto;
                height: 115px;
                border: 2px solid red;
                border-radius: 12px;
            }
        </style>
    </head>
    <body>
        <div id="page">
            <input id="name">
            <button onClick="check()">sign in</button>
        </div>
    <script>
        function check (){
            if(document.getElementById("name").value==="ARCoder"||document.getElementById("name").value==="test"||document.getElementById("name").value==="tsc"){
            start();
            }
        }
        document.getElementById("name").oninput = function() {check()};
    function prank (){
            document.getElementById("book").innerHTML="<h1>Prankster <em>and his</em> Neighbor</h1><hr><h2>Intro</h2><hr><p>Prankster did not like his Neighbor so he pranks him therefor everyone calls him Prankster.</p><hr><h2>Chapter 1</h2><hr><p>Prankster asked his Neighbor if he wanted to have lunch with him, his Neighbor said of course. Why not? so Prankster </p>";
        }
        function war (){
            document.getElementById("book").innerHTML="";
        }
        function start (){
            document.getElementById("page").innerHTML='<div id="book"></div>        <div id="books">        <button onClick="prank()">        <svg style="width:80;height:98;cursor:pointer;border-radius:5px">        <rect width="80" height="95" style="fill:rgb(0,0,255);stroke-width:3;stroke:rgb(0,0,0)" />        <path d="M 40 49 22 12 10 49" stroke="rgb(255, 0,0)" fill="rgb(9, 255, 0)" stroke-width="2" transform="scale(0.9,0.9) translate(-2,0)">        </path>    <path d="M 36 35  13 35" stroke="rgb(255, 0,0)" fill="rgb(255, 130, 255)" stroke-width="2" transform="scale(0.9,0.9) translate(-2,0)"></path>    <text x="7" y="73">Prankester</text></svg></button>    <button onClick="war()">        <svg style="width:80;height:98;cursor:pointer;border-radius:5px">        <rect width="80" height="95" style="fill:rgb(0,0,255);stroke-width:3;stroke:rgb(0,0,0)" />        <path d="M 40 49 22 12 10 49" stroke="rgb(255, 0,0)" fill="rgb(9, 255, 0)" stroke-width="2" transform="scale(0.9,0.9)translate(-2,0)">        </path>    <path d="M 36 35  13 35" stroke="rgb(255, 0,0)" fill="rgb(255, 130, 255)" stroke-width="2" transform="scale(0.9,0.9) translate(-2,0)"></path>    <text x="5" y="73">Clown War</text></svg></button>    <button onClick="war()">        <svg style="width:80;height:98;cursor:pointer;border-radius:5px">    <rect width="80" height="95" style="fill:rgb(0,0,255);stroke-width:3;stroke:rgb(0,0,0)" />    <text x="4" y="30" font-size="30">TSC</text>    <text x="4" y="51" font-size="15">No Title</text>   </svg></button>    </div>';
        }
    </script>
    </body>
</html>
