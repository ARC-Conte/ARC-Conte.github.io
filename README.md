<html>
    <head>
        <meta charset="utf-8">
        <title>linker</title>
        <style>

      ::selection {
        background: rgb(160, 6, 6);
      }

      ::-webkit-scrollbar {
        width: 10px;
      }

      i {
        user-select: none;
      }

      ::-webkit-scrollbar-track {
        background: red;
      }

      ::-webkit-scrollbar-thumb {
        background: linear-gradient(rgb(60, 255, 0),rgb(87, 82, 87));
      }

      ::-webkit-scrollbar-thumb:hover {
        background: linear-gradient(rgb(87, 82, 87),rgb(60, 255, 0));
      }

      

            sup{
                color: brown;
            }
            div{
                font-size: 17px;
            }
            :root {
                --theam: rgb(0, 0, 0);
                --text-theam: rgb(0, 255, 30);
                --arc-theam: rgb(10, 245, 96);
                --arc-text-theam: rgb(255, 255, 3);
                --cpc-theam: rgb(0, 0, 0);
                --cpc-text-theam: rgb(196, 21, 21);
            }
            input{
                color: rgb(0, 255, 30);
                background-color: rgb(0, 0, 0);
                width:172px;
            }
            button{
                color: red;
                background-color: black;
                border: double;
            }
            h1{
                color: brown;
                text-align: center;
            }
            body{
                background-color: var(--theam);
                color: var(--text-theam);
                text-align: center;
            }
            #red{
                color: red;
            }
            #window{
                color: white;
                background-color: rgb(13, 0, 255);
                padding:10px;
                margin: 5px 0px 5px 0px;
            }
            .icon-arc{
                width: 50px;
                border: 2px solid green;
                background-color: var(--arc-theam);
            }
            .arc{
                color: var(--arc-text-theam);
            }
            .icon-cpc{
                width: 50px;
                border: 2px solid green;
                background-color: var(--cpc-theam);
            }
            .cpc{
                color: var(--cpc-text-theam);
            }
            .icon-tsc{
                width: 50px;
                border: 2px solid green;
                background-color: rgb(30, 0, 255);
            }
            .icon-no{
                width: 50px;
                border: 2px solid green;
                background-color: black;
            }
            .rating{
                width: 30px;
                border: 2px solid green;
            }
            option{
                color: red;
                background-color: green;
            }
            .a{
                color: rgb(75, 85, 110);
                background-color: grey;
            }
            hr{
                border-top: 1px solid blue;
                border-bottom: 1px solid green;
            }
            .page{
                color: rgb(97, 94, 97);
                text-align: left;
            }
            h2{
                text-align: center;
            }
            h3{
                text-align: center;
            }
            #id-card {
                border:1px solid black;
                border-radius:5px;
                width: 200px;
                font-family: monospace;
                height: 75px;
                padding: 6px;
                background: rgb(0, 163, 68);
            }
            #id-name {
                float: right;
            }
            .news{
                border-radius:5px;
                width:125px;
                height: 75px;
                border: none;
                background: grey;
            }
            .news:hover{
                border-radius:10px;
                width:125px;
                height: 75px;
                border: none;
                background: blue;
            }
            ul{
                text-align: left;
            }
            ol{
                text-align: left;
            }
            button:hover{
                border: dotted;
            }
            .l{
                font-size:xx-large;
            }
        </style>
    </head>
        <body>
            <dialog open=""><h3>New Notifcation</h3>
                <div style="max-height: 150px; overflow: auto">
                <code>
                    <h1><em>NEW</em> SHOP</h1>
                    <p>go to the shop with this link</p><br>
                    <button onClick="n5()">Shop</button>
                </code>
            </div>
            <form method="dialog"><br>
                <button>Close</button>
            </form>
        </dialog>
        <hr>
        <h1>------------LINKER<sup>v<span id="v"></span></sup>------------</h1>
        <hr>
    <div id="message">  
        
        <label>username:
        <input id="name" type="text" placeholder="alaways needed."><br><br>
        password:
        <input id='password' type='password' placeholder="needed if its an acount.">
        </label>
        <br>
        <button id="button" type="button">enter</button>
        </div><br><hr>
        <div style="overflow:auto; height: 500px;">
        <button class="news"><h2 onClick="n1()">see: new updates</h2></button><br>
        <br><button class="news"><h2 onClick="n2()">see: show and tell</h2></button><br>
        <br><button class="news"><h2 onClick="n3()">see: A.R.C. story</h2></button><br>
        <br><button class="news"><h2 onClick="n4()">see: getting a license</h2></button><br>
        <br><button class="news"><h2 onClick="n5()">see: shop</h2></button></div>
  <script>// TO MUCH CODE{
  
  var button = document.getElementById("button");
  document.getElementById("v").textContent="1.0.2";
  var onButtonClick = function() {
    var cpass =["cpc","ModSquad","tech"];
    var apass =["ARCoder","code","sci"];
    var password = document.getElementById("password").value;
    var name = document.getElementById("name").value;
    var greeting="<div id='window'>reload and type in a new linker<sup id='red'>code</sup></div>";
    var other = "<div class='a'><h2>news</h2><p></p><div>";
    var ok = true;
    //{
    if(name===apass[0] && password===apass[1] || name===apass[2] && password===apass[1]){
        greeting ="<div id='window'>Your LINKER<sup id='red'>Code</sup> was succesful.</div><div class='arc'><br><svg style='width:94px; height: 71px; border-radius:5px'><rect x='2' y='18' fill='rgb(16, 133, 0)' width='92' height='50'></rect><text font-size='25' font-family='Cursive' x='4' y='51'>ARC</text><text fill='red' font-size='25' font-family='Cursive' x='36' y='50'>C</text>         <text transform='rotate(-7 20,40)' font-family='Verdana' x='56' y='43'>oder</text>            <text transform='rotate(8 25,40)' font-family='Verdana' x='64' y='54'>👨🏻‍💻</text>  <text fill='red' transform='rotate(-7 20,40)' font-family='Verdana' x='54' y='42'>oder</text></svg> <label><select><option>bages:</option><option>gold member 🥇</option><option>coder 10💻  </option></select></label><br><br> Welcome, A.R.C.</div><span id='note'>are you geting the new verison</span>";
        ok = true;
    }else if(name==="tsc" && password==="ttt" || name==="lab" && password==="ttt"){
        greeting="<div id='window'>Your LINKER<sup id='red'>Code</sup> was succesful.</div><div class='tsc'><br><svg style='width:94px; height: 71px; border-radius:5px'>  <rect x='2' y='18' fill='rgb(16, 133, 0)' width='92' height='50'></rect>            <text font-size='25' font-family='Cursive' x='3' y='51'>TSC</text>            <text fill='red' font-size='25' font-family='Cursive' x='36' y='50'>C</text>            <text transform='rotate(-7 20,40)' font-family='Verdana' x='52' y='43'>at</text>            <text fill='red' transform='rotate(-7 20,40)' font-family='Verdana' x='51' y='42'>at</text>            <text transform='rotate(-8 41,40)' font-family='Verdana' x='69' y='43'>😻</text>            <text transform='rotate(24 41,40)' font-family='Verdana' x='57' y='50'>😺</text>        </svg> rating: <img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><label><select><option>bages:</option><option>join linker 🖥 </option></select></label><br><br> Welcome, T.S.C.</div>";ok = true;
        
    }else if(name===cpass[0] && password===cpass[1] || name===cpass[2] && password===cpass[1]){
        greeting="<div id='window'>Your LINKER<sup id='red'>Code</sup> was succesful.</div><div class='cpc'>C.P.C.<br><img class='icon-cpc' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/avatars/robot_male_2.png'> rating: <img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><label><select><option>bages:</option><option>join linker 🖥 </option></select></label><br><br> Welcome, C.P.C.</div>";
        ok = true;
    }else if(name==="cpc"){
        greeting="<div class='page'><h2>C.P.C.</h2><ul>skills:<li>coding(pjs)<li>trains</ul><h3>entery 1</h3><p>your text here</p><h3>entery 2</h3><p>your text here</p></div>";
    }else if(name==="arc"){
        greeting="<div class='page'><h2>A.R.C.</h2><ul>skills:<li>coding(html, java, pjs, jQuery)<li>light show master<li>electronics</ul><h3>Show and tell</h3><p></p><h3>entery 2</h3><p>your text here</p><h3>entery 3</h3><p>your text here</p></div>";
            ok=false;
    }else if(name==="cards"){
            greeting="<div id='id-card'><h3>A.R.C.</h3><p>coding</p></div>";ok=false;
    }else{
        ok=true;
    }
        
    
    //}
    document.getElementById("message").innerHTML = greeting;
    if(ok){
    document.getElementById("message").innerHTML += other;
    }
  };
  button.addEventListener("click", onButtonClick);
  var n1 = function(){
      var message ="<h2>updates</h2><ul>reqests:</ul><ol>updates in progres:</ol><ul>finshed:<li>a Christmas theam ~<span>linker</span><li>show and tell buttons ~cpc</ul>";
      document.getElementById("message").innerHTML=message;
  };
  var n2 = function(){
      var message ="<h2>show and tell</h2><h3>Canenball ~ C.P.C.</h3><p>this engine was a budget train it had no front coupler, it was all black, and no way to reverse from the transformer. I wanted to upgrade this engine panting it was a good start. For the way i use my trains i need a front coupler but i was not sure how to do it. Recently at a train show i found in a junk bin under a table a shell with a front coupler. It was only $2 and it was just what I had needed. when it was new in 1973 it was only avalibale in a set called the Canenball Express</p>";
      document.getElementById("message").innerHTML=message;
  };
  var n3 = function(){
      var message ="<h2>A.R.C. story</h2><p>Jack went walking and he found a man on the edge of a cliff, so he went to help him but going toward him was a bear. He quickly ran to his house to get his gun and kill the bear. Jack ran and ran and he was going so fast he tripped but he could not stop thing of how scared the man must be so he got back up and ran to his house.</p>";
      document.getElementById("message").innerHTML=message;
  };
  var n4 = function(){
      var message ="<h2>Want to post on <span>Linker</span></h2>";
      document.getElementById("message").innerHTML=message;
  };
  var n5 = function(){
      var message ="<h2>LINKER Shop</h2><ul style='font-size: 20px;'>items:<li>1 star 10 <sup>-linker-</sup><li>better avatar 15 <sup>-linker-</sup><li>1 star 10 <sup>-linker-</sup></ul>";
      document.getElementById("message").innerHTML=message;
  };
  //}</script>
    </body>
</html>
