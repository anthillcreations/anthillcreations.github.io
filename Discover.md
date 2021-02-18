<!DOCTYPE html>
<html>
<head>
<style>
.button {
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}


.button2 {background-color: #008CBA;   } /* Blue */
.button3 {background-color: #f44336;  } /* Red */ 
.button4 {background-color: #e7e7e7; color: black;    } /* Gray */ 
.button5 {background-color: #555555;    }
.button6 {background-color: #4CAF50;    }
.button7 {background-color: #f44336;  }

body {
  background-image: url('1.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;  
  background-size: cover;
}

.first {
 position: absolute;
 top: 50%;
 left: 25%;

}

.second {
 position: absolute;
 top: 90%;
 left: 90%;

}


</style>
</head>
<body>

<div class="first">
<button class="button button6" onclick="document.location='level 1.html'"> Level 1</button>
<button class="button button2" onclick="document.location='level 2.html'"> Level 2</button>
<button class="button button7" onclick="document.location='level 3.html'"> Level 3</button>
<button class="button button4" onclick="document.location='level 4.html'"> Level 4</button>
<button class="button button5" onclick="document.location='level 5.html'"> Level 5</button></br></div>
<div class="second">
<button class="button button3" onclick="document.location='index.html'"> HOME</button></div>

</body>
</html>