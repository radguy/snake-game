# snake-game
snake/*
JavaScript Snake
By nick
*/
body {
	margin:0px;
	padding:0px;
}

#game-area {
	margin:0px;
	padding:0px;
}

#high-score {
    position: relative;
    left: 200px;
    bottom: 50px;
}

#mode-wrapper {
    color: #ffffff;
    font-family: Verdana, arial, helvetica, sans-serif; 
    font-size: 14px;
    
}

#game-area:focus { outline: none; }

a.snake-link, a.snake-link:link, a.snake-link:visited {
  color: #FCFC54; 
}

a.snake-link:hover {
  color: #FfFf54; 
}

.snake-pause-screen {
    font-family: Verdana, arial, helvetica, sans-serif; 
    font-size: 14px;
    position:absolute;
    width:300px;
    height:80px;
    text-align:center;
    top:50%;
    left:50%;
    margin-top:-40px;
    margin-left:-150px;
    display:none;
    background-color:black;
    color:white;
}

.snake-panel-component {
    position: absolute;
    font-family: Verdana, arial, helvetica, sans-serif; 
    font-size: 14px;
    color: #ffffff;
    text-align: center;
    background-color: #FC5454;
    padding: 8px;
    margin: 0px;
}

.snake-snakebody-block {
    margin: 0px;
    padding: 0px;
    background-color: #Fy0021;
    position: absolute;
    border: 0px solid #000080;
    background-repeat: no-repeat;
}

.snake-snakebody-alive {
   background-image: url('./images/snakeblock.png');
}
.snake-snakebody-dead {
   background-image: url('./images/deadblock.png');
}

.snake-food-block {
    margin: 0px;
    padding: 0px;
    background-color: #FF0000;
    border: 0px solid #000080;
    position: absolute;
}

.snake-playing-field {
    margin: 0px;
    padding: 0px;
    position: absolute;
    background-color: #0000A8;
    border: 0px solid #0000A8;
}

.snake-game-container {
    margin: 0px;
    padding: 0px;
    border-width: 0px;
    border-style: none;
    zoom: 1;
    background-color: #FC5454;
    position: relative;
}
            
.snake-welcome-dialog {
    padding: 8px;
    margin: 0px;
    background-color: #000000;
    color: #ffffff;
    font-family: Verdana, arial, helvetica, sans-serif;
    font-size: 14px;
    position: absolute;
    top: 50%;
    left: 50%;
    width: 300px;
    /*height: 150px;*/
    margin-top: -100px;
    margin-left: -158px;
    text-align: center;
    display: block;
}

.snake-try-again-dialog {
    padding: 8px;
    margin: 0px;
    background-color: #000000;
    color: #ffffff;
    font-family: Verdana, arial, helvetica, sans-serif;
    font-size: 14px;
    position: absolute;
    top: 50%;
    left: 50%;
    width: 300px;
    height: 100px;
    margin-top: -75px;
    margin-left: -158px;
    text-align: center;
    display: none;

