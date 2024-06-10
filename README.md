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
                width:185px;
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

                   
        <h1>LINKER<sup>v<span id="v"></span></sup></h1>
    <div id="message">  
        
        <label>username:
        <input id="name" type="text" placeholder="alaways needed."><br><br>
        password:
        <input id='password' type='password' placeholder="needed if its an acount.">
        </label>
        <br>
        <button id="button" type="button">enter</button>
        </div><br>
        <div style="overflow:auto; height: 500px;">
        <h2>News</h2>
        <h3>For new members:</h3>
        <p>You can get a higher rating if you do spectacular things or you get a new award.</p>
  <script>  
  var button = document.getElementById("button");
  document.getElementById("v").textContent="1.0.2";
  var onButtonClick = function() {
    var cpass =["cpc","ModSquad","tech"];
    var apass =["ARCoder","code","sci"];
    var mpass =["painthon","slc","chem"];
    var password = document.getElementById("password").value;
    var name = document.getElementById("name").value;
    var greeting="<div id='window'>reload and type in a new linker<sup id='red'>code</sup></div>";
    var other = "<div class='a'><h2>news</h2><p></p><div>";

    //{
    if(name===apass[0] && password===apass[1] || name===apass[2] && password===apass[1]){
        greeting ="<div id='window'>Your LINKER<sup id='red'>Code</sup> was succesful.</div><div class='arc'><br><svg style='width:94px; height: 71px; border-radius:5px'><rect x='2' y='18' fill='rgb(16, 133, 0)' width='92' height='50'></rect><text font-size='25' font-family='Cursive' x='4' y='51'>ARC</text><text fill='red' font-size='25' font-family='Cursive' x='36' y='50'>C</text>         <text transform='rotate(-7 20,40)' font-family='Verdana' x='56' y='43'>oder</text>            <text transform='rotate(8 25,40)' font-family='Verdana' x='64' y='54'>👨🏻‍💻</text>  <text fill='red' transform='rotate(-7 20,40)' font-family='Verdana' x='54' y='42'>oder</text></svg> <label><select><option>bages:</option><option>gold member 🥇</option><option>coder 10💻  </option></select></label><br><br> Welcome, A.R.C.</div><span id='note'>are you geting the new verison</span>";

    }else if(name==="tsc" && password==="ttt" || name==="lab" && password==="ttt"){
        greeting="<div id='window'>Your LINKER<sup id='red'>Code</sup> was succesful.</div><div class='tsc'><br><svg style='width:94px; height: 71px; border-radius:5px'>  <rect x='2' y='18' fill='rgb(16, 133, 0)' width='92' height='50'></rect>            <text font-size='25' font-family='Cursive' x='3' y='51'>TSC</text>            <text fill='red' font-size='25' font-family='Cursive' x='36' y='50'>C</text>            <text transform='rotate(-7 20,40)' font-family='Verdana' x='52' y='43'>at</text>            <text fill='red' transform='rotate(-7 20,40)' font-family='Verdana' x='51' y='42'>at</text>            <text transform='rotate(-8 41,40)' font-family='Verdana' x='69' y='43'>😻</text>            <text transform='rotate(24 41,40)' font-family='Verdana' x='57' y='50'>😺</text>        </svg> rating: <img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><label><select><option>bages:</option><option>join linker 🖥 </option></select></label><br><br> Welcome, T.S.C.</div>";
        
    }else if(name===cpass[0] && password===cpass[1] || name===cpass[2] && password===cpass[1]){
        greeting="<div id='window'>Your LINKER<sup id='red'>Code</sup> was succesful.</div><div class='cpc'>C.P.C.<br><img class='icon-cpc' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/avatars/robot_male_2.png'> rating: <img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><label><select><option>bages:</option><option>join linker 🖥 </option></select></label><br><br> Welcome, C.P.C.</div>";
    }else if(name===mpass[0] && password===mpass[1] || name===mpass[2] && password===mpass[1]){
        greeting="<div id='window'>Your LINKER<sup id='red'>Code</sup> was succesful.</div><div class='painthon'>painthon<br><img class='icon-painthon' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/avatars/robot_male_2.png'> rating: <img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><img class='rating' src='https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/space/star.png'><label><select><option>bages:</option><option>join linker 🖥 </option></select></label><br><br> Welcome, painthon<br><ul>Fun Things<li>memfist kity pack<li>christmas pack<li>tescora park</ul></div>";
    }else if(name==="cpc"){
        greeting="<div class='page'><h2>C.P.C.</h2><ul>skills:<li>coding(pjs)<li>trains</ul><h3>entery 1</h3><p>your text here</p><h3>entery 2</h3><p>your text here</p></div>";
    }else if(name==="arc"){
        greeting="<div class='page'><h2>A.R.C.</h2><ul>skills:<li>coding(html, java, pjs, jQuery)<li>light show master<li>electronics</ul><h3>Show and tell</h3><p></p><h3>entery 2</h3><p>your text here</p><h3>entery 3</h3><p>your text here</p></div>";
           
    }else if(name==="cards"){
            greeting="<div id='id-card'><h3>A.R.C.</h3><p>coding</p></div>";
    }else{
    }
        
    
    
    document.getElementById("message").innerHTML = greeting;
  };
  button.addEventListener("click", onButtonClick);
  </script>

