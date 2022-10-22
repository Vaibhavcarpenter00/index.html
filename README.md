#index.html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>world wide web</title>
  <style>
    body{
    margin: 0;
    padding: 0;
    width:100%;
    height: 280vh;
  }
.main{
    width:260%;
    height:100%;
    background:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)),url("/IMG-20220129-WA0008.jpg");
    background-image:cover;
    background-size: cover;
    text-decoration-style: solid black;
    background-repeat:no-repeat;
    top: 0px;
}
.nav{
  background-position: fixed;
}
.logo{
  color: brown;
  font-size: 20px;
  font-family: arial;
  padding-left:100px;
  float: left;
  padding:0px;
  margin-top:10px;
}
h1 {
  border: 2px solid green;
  border-style: dashed;
  margin-top: 5px;
  margin-left: 1px;
}
.icon{
    border-width: 2px;
    border-style: solid black;
    width: 940px;
    height:40px;
    background: black;
    position: fixed;
}
.angular{
  width:102px;
  height: 100%;
  float: left;
  justify-content: center;
  color: white;
  margin-top:0px;
}
ul{
  float: left;
  display: flex;
  align-items: center;
  color: white;
  margin-top:10px;
}
ul li{ 
  list-style: none;
  margin-top:1px;
  margin-left:20px;
  font-size: 15px;
  padding: 4px;
  color: white;
}
ul li a{
  text-decoration: none;
  padding: 5px;
  color: wheat;
}
.sarch{
  margin-top: 5px;
  margin-left: 690px;
}
.sarc{
  width: 100px;
  height: 10px;
  background: transparent;
}
img{
  width: 35px;
  height: 35px;
  float: right;
  margin-top: 5px;
  margin-right: 90px;
}

.red {
text-decoration-color: none;
background-color:darkgrey;
}
ul li a:hover{
background-color:darkgray;
}
h1:hover{
background-color: white;
}
.card{
     width: 100%;
     height: 100%;
     display: flex;
     align-items: left;
     justify-content: left;
   }
   .inner-card{
     margin-top: 20%;
     margin-right: 80%;
     display: flex;
     align-items: center;
     margin-right: 0%;
     justify-content: center;
     transition: 1s;
     opacity: 0;
   }
   .on {
      opacity:1;
      transform: translate 1s;
    }
   .btn3{
      width: 50px;
      height: 50px;
      backface-visibility: hidden;
    }
  .form{
    width: 200px;
    height: 450px;
    margin-top: -60%;
    margin-left: 225%;
     background-image:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)), url("/Snapchat-1395613616.jpg");
     background-size: cover;
     background-image: cover;
     padding: 0px 15px;
     color: ghostwhite;
     overflow: hidden;
   }
  .onn{
     width: 200px;
     height: 450px;
     background-image:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)), url("/Snapchat-1395613616.jpg");
     padding: 0px 15px;
     transition: background 3s;
   }
   ul{
      margin-left: 50px;
   }
   h2{
     font-size: 25px;
     align-items: center;
     justify-content: center;
      margin-left: 30px;
   }
   small{
     color: red;
   }
   input {
     border-color: coral;
     padding: 10px;
     color: white;
   }
   .name{
     margin-top: 3px;
     border-radius: 20px;
     background: transparent;
   }
   .phone {
     margin-top: 3px;
     border-radius: 20px;
     background: transparent;
   }
   .email{
     margin-top: 3px;
     border-radius: 20px;
     background: transparent;
   }
   .password{
     margin-top: 3px;
     border-radius: 20px;
     background: transparent;
   }
   .compassword{
     margin-top: 3px;
     border-radius: 20px;
     background: transparent;
   }
   .check{
     margin-top: 3px;
     border-radius: 20px;
     background: transparent;
   }
   .formerror{
     color: red;
     font-size: 10px;
   }
   button{
     background-color: blue;
   }
   .submit{
     width: 210px;
     margin-top: 20px;
     border-radius: 10px;
     height: 30px;
     color: blue;
     background-color: blue;
   }
   span{
     color: black ;
     font-size: 20px;
   }
   input::placeholder {
    color: white;
   }
   .btn{
      position: relative;
      background-color: seashell;
      position: fixed;
      margin-top: 1%;
      width: 60px;
      height: 30px;
      border-radius: 6px;
      margin-left: 64%;
      border: 0;
      outline: 0;
      cursor: pointer;
      transition: background 1s;
    }
    button .btn2{
      display: block;
      width: 1px;
      height:1px;
      border-radius: 1%;
      margin-left:px;
      margin-top: -12px;
      background: whitesmoke;
      transition: background 0.5s,
      margin-left 0.5s;
    }
    .active{
      background: blue;
    }
    .active .btn2{
      background-color:red;
      margin-left: 0px;
    }
    .camera{
      position: absolute;
      margin-top: 150px;
      margin-left: 50px;
      float: center;
      overflow: hidden;
      justify-content: center;
      background: transparent;
    }
    .img2{
      width: 70px;
      height: 70px;
      float: center;
      justify-content: center;
      background: transparent;
    }
    p{
      margin-top: 100px;
      margin-left:50px;
      width: 220px;
      font-family:20px;
      font-family: sans-serif;
      color: lime;
    }
    .photo{
      position: relative;
      width: 102%;
      margin-top: -16.5%;
      background-image: linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5));
      background-repeat: no-repeat;
      background-size: cover;
    }
    .li-decoret{
     margin-top: 5%;
     margin-left: 30%;
     background-color: black;
    }
    .center{
      align-items: center;
      margin-left: -10%;
    }
    .maneg{
      margin-top: 16.5%;
    }
    .Gellery{
     position: relative;
     background-attachment: scroll;
     background: transparent;
    }
    .img4{
      width:200px;
      height:200px;
      padding: -30px;
      margin-top: 57px;
    }
    .img5{
       width:200px;
       height:200px;
    }
    .img6{
        width:200px;
        height:200px;
    }
    .img7{
        width:200px;
        height:200px;
    }
    .img8{
       width:200px;
       height:200px;
    }
    .img9{
         width:200px;
         height:200px;
    }
    .img10{
         width:200px;
         height:200px;
    }
    .img4:hover{
     transform: scale(1.4);
    }
    .img5:hover{
     transform: scale(1.4);
    }
    .img6:hover {
      transform: scale(1.4);
    }
    .img7:hover {
      transform: scale(1.4);
    }
    .img8:hover {
      transform: scale(1.4);
    }
    .img9:hover {
      transform: scale(1.4);
    }
    .fieldset{
      background-color: peachpuff;
    }
    .problem{
      width: 100%;
      box-sizing: border-box;
    }
      
    div.content{
      width: 100%;
      padding: 50px 0px;
      margin-top:-10%;
    }
    h2{
      color: red;
      margin-top:10%;
      text-align: center;
    }
    pre{
      text-align: center;
      margin-left: 30px;
      margin-top: -20px;
    }
    .img0{
      margin-right: 400px;
      width: 70px;
      height: 70px;
    }
    .img-logo{
     margin-top: -8%;
     margin-right: 22%;
     padding: -100px;
    }
    .pre{
      font-size: 10px;
      margin-left:40%;
    }
    h3{
      margin-left:55%;
    }
    .fieldset1{
      width: 100%;
      display: flex;
      background-color: black;
      margin-left: -1%;
    }
    .s1{
      margin-top: 10%;
      margin-left: 30px;
      color: skyblue;
    }
    .angular1{
       margin-top: 14%;
    }
    .angular2{
       margin-top: 14%;
    }
    .angular3 {
      margin-top: 14%;
    }
    .angular4 {
      margin-top: 14%;
    }
    li{
      list-style: none;
      padding: 7px 50px;
    }
    h4{
      color: red;
      font-size: 20px;
      margin-left: 10%;
    }
    .p{
      margin-top: -10%;
      display: inline-block;
    }
    .s5{
      float: right;
      margin-top: -10%;
      margin-right: -160%;
      background: transparent;
    }
    .btnl{
      width:100px;
      height: 42px;
      float: right;
      margin-top: -10%;
      margin-right: -190%;
      color: black;
      background-color: red;
    }

    
  </style>
</head>
<body>
  <div class="main">
    <div class="camera">
      <img class="img2" src="/Screenshot_2022-10-15-12-27-05-044~2.jpeg" alt="not available">
      <p> capturing the movement that<br> captivet your heard </p>
    </div>
    <div class="nav">
      <div class="icon">
        <h1 class="logo">world wide website</h1>
        <img class="img" src="/Screenshot_2022-10-14-22-09-02-344.jpeg" alt="🖥️">
      <div class = "angular">
          <ul>
             <li datefilter= "photo" class="red"> <a href="#">home </a> </li>
             <li> <a href="#">video </a> </li>
             <li>  <a href="#">about</a> </li>
             <li> <a href="#">content</a></li>
          </ul>
      </div>
      <div class="sarch">
        <input type="text" class="sarc" id="" placeholder="sarch..." >
      </div>
      </div>
       <div class="card">
         <button onclick="ajay()" id="btn" class="btn" type="submit"><span class="btn2">Rgstr</span></button>
         <div class="inner-card" id="dreg">
           <div class="forms">
             <form action="php/name"class="form" id="form" name="myform" onsubmit="return   validateform()"  method="post">
               <h2>Ragister now</h2>
               <div class="urname" id="name">
                 <input type="text" class="name" name="name" placeholder="enter your name"><br>
                 <span class="formerror"><b></b></span>
               </div>
               <div class="cphone" id="phone">
                 <input type="number" class="phone" name="phone" placeholder="enter your phone number"><br>
                 <span class="formerror"><b></b></span>
               </div>
               <div class="cemail" id="email">
                 <input type="text" class="email" name="email" placeholder="enter your email" id=""><br>
                 <span class="formerror"><b></b> </span>
               </div>
               <div class="cpassword" id="pass">
                 <input type="text" placeholder="password" class="password" name="pass"><br>
                 <span class="formerror"> <b></b></span>
               </div>
               <div class="ccpossword" id="cpass">
                 <input type="text" class="compassword" name="cpass" placeholder="enter your comparm password"><br>
                 <span class="formerror"><b></b></span>
               </div>
               <div class="ccheck">
                 <input type="checkbox" class="check" id=" " required>Remember me<br>
               </div>
               <div class="csubmit">
                 <button class="submit" value="submit"><span>submit
                   </span></button>
               </div>
             </form>
           </div>
         </div>
    </div>
  </div>
 <fieldset class="fieldset">
   <div class="problem">
     <div class="content">
       <h2>our information</h2>
       <pre>what our members says</pre>
       <img class="img0" src="/Screenshot_2022-10-15-15-30-43-821~2.jpeg" alt="">
       <p class="pre"> While receiving an international call, if an Indian number or no number is displayed on your phone, please inform on DoT </p>
     </div>
     <div class="img-logo">
       <h3>*vaibhav carpenter</h3>
       <img class="img11" src="/Screenshot_2022-10-15-18-19-30-077~2.jpeg" alt="">
       <img class="img12" src="/Screenshot_2022-10-15-18-23-19-817.jpeg" alt="">
       <img class="img13" src="/Screenshot_2022-10-15-18-23-04-429.jpeg" alt="">
     </div>
   </div>
</fieldset>
<div class=" photo">
  <div class="li-decoret">
    <ul class="center">
      <li class="red"> <a href="#">Gellery </a> </li>
      <li> <a href="#">neture </a> </li>
      <li> <a href="#">fasion</a> </li>
    </ul>
  </div>
  <div class="maneg">
    <div class="Gellery">
      <img class="img4" src="/IMG-20220129-WA0008.jpg" alt="">
      <img class="img5" src="/IMG-20220605-WA0007.jpg" alt="">
      <img class="img6" src="/IMG_20220203_210230_444.jpg" alt="">
      <img class="img7" src="/IMG_20220502_132440_477.jpg" alt="">
      <img class="img8" src="/IMG_20220531_170618_232.jpg" alt="">
      <img class="img9" src="/IMG_20220617_015024_972.jpg" alt="">
    </div>
  </div>
</div>
<fieldset class="fieldset1">
  <div class="subscribe">
    <h4>subscribe our newsletter</h4>
    <p class="p"> place to stay in along with synonyms and antonyms </p>
  
    <input type="text" class="s5" name="firstName" id="input" placeholder="enter email....">
    <input type="submit" class="btnl" name="firstName" id="bg">
  </div>
  <div class="angular1">
    <h3 class="s1">usefull link</h3>
      <li > <a href="#">home </a> </li>
      <li> <a href="#">video </a> </li>
      <li> <a href="#">about</a> </li>
      <li> <a href="#">content</a></li>
  </div>
   <div class="angular2">
     <h3 class="s1">fetion link</h3>
      <li > <a href="#">all</a> </li>
      <li> <a href="#">Gellery </a> </li>
      <li> <a href="#">fetion</a> </li>
      <li> <a href="#">neture</a></li>
  </div>
   <div class="angular3">
     <h3 class="s1">contact link</h3>
     <li> <a href="#">look </a> </li>
     <li> <a href="#">photo </a> </li>
     <li> <a href="#">service</a> </li>
     <li> <a href="#">content</a></li>
   </div>
   <div class="angular4">
     <h3 class="s1">about</h3>
     <li> <a href="#">look </a> </li>
     <li> <a href="#">photo </a> </li>
     <li> <a href="#">service</a> </li>
     <li> <a href="#">content</a></li>
   </div>
</fieldset>
<script>
       var btn = document.getElementById("btn");
     var card = document.getElementById("dreg");
     var form = document.getElementById("form");
    function ajay() {
       btn.classList.toggle("active");  
       card.classList.toggle("on");
       form.classList.toggle("onn");
    }
    var form = document.getElementById("form");
    function vaibhav() {
    form.style.height ="600px";
    }
    function clearErrors(){
      errors = document.getElementsByClassName("formerror");
      for(let itam of errors){
        itam.innerHTML="";
      }
    }
    function seterror(id, error){
       element= document.getElementById(id);
       element.getElementsByClassName("formerror")[0].innerHTML=error;
    }
    function validateform(){
      var returnval = true;
      clearErrors();
      var name = document.forms["myform"]["name"].value;
        if(name.length<5){
          seterror("name","*the name is to short");
          returnval = false;
       }
      var phone = document.forms["myform"]["phone"].value;
        if (phone.length < 10) {
          seterror("phone", "*the number is to short");
          returnval = false;
      }
      var email = document.forms["myform"]["email"].value;
        if (email.length < 20) {
          seterror("email", "*the email is to short");
          returnval = false;
      }
      var pass = document.forms["myform"]["pass"].value;
        if (pass.length < 5) {
          seterror("pass", "*the password is to short");
          returnval = false;
      }
       var cpass = document.forms["myform"]["cpass"].value;
        if (cpass != pass) {
          seterror("cpass", "*the password is not equal ");
        returnval = false;
      }
      return returnval;
     }
     
     function input(){
      var val = document.getElementsByClassName("bg");
      for(let itam of errors){
        itam.innerHTML="";
      }
     }
  
</script>
</body>
</html>

