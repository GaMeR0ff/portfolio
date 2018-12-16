<!DOCTYPE html>

<html>

<head>
    <meta charset="UTF-8">
    <title>Товары для подарка</title>
    <script type='text/javascript' src="https://code.jquery.com/jquery-3.3.1.js"></script>
    <style>
              body {
background-image: url('img/gamer.jpg');
background-repeat: no-repeat;
background-size: 1275px ;
min-height: 1200px;

overflow-x: hidden;
}

body:before {
  background:
  url("img/fon2.jpg") no-repeat center center;
  bottom: 0;
  content: "";
  height: 295px;
  left: 0;
  position: absolute;/*абсолютное позиционирование*/
  right: 0;
  top: 715px;
  height: 1365px;
  }


#Kla{
  position:absolute;
  left:5px;
  top:-40px;
  width: 240px; 
  }
#r{
  background-color: Transparent;
  border: none;
  cursor:pointer;
  overflow: hidden;
  outline:none;
  width: 225px;
  height: 170px;
  z-index: 400;
  position: absolute;
  left: -1px;
}
.djrheu{
  background-color: #0000007d;
  width: 100%;
  height: 100%;
  position: fixed;
  top: 0px;
  left: 0px;
  z-index: 5000;
  display: none;
}
.dyenhb{
  background-image: url('img/gamer2.jpg') ;
  position: fixed;
  width: 210px;
  height: 200px;
 top : 250px;
 left: 500px;

}
.kl{
  width: 200px;
}
#kl1{
  top:5px;
  left: 20px;
  display: flex;
}
#kl1:hover{
  transform: scale(2, 2);
}

a.tr{
  display: inline-block;
  font-size: 1.1em;
  width:30px;
  text-decoration:none;
  text-align:center;
  font: bold 14px arial;
  text-transform: uppercase;
  padding: 10px 15px;
  margin: 20px auto;
 
  color: #ccc;
  background-color: #555;
  background-image: linear-gradient(top, #888 0%, #555 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0, #888), color-stop(1, #555));
  background-image: -moz-linear-gradient(top, #888 0%, #555 100%);
  background-image: -o-linear-gradient(top, #888 0%, #555 100%);
  border: none;
  border-radius: 3px;
  text-shadow: 0px -1px 0px #000;
  box-shadow: 0px 1px 0px #666,0px 5px 0px #444,0px 6px 6px rgba(0, 0, 0, .6);
  -webkit-transition: ease .15s all;
  -moz-transition: ease .15s all;
  -o-transition: ease .15s all;
  transition: ease .15s all;
  -webkit-animation: none;
   -moz-animation: none;
   -o-animation: none;
    animation: none;
  }
  a.tr:hover, a.bott:focus{
  -webkit-animation: linear 1.2s light infinite;
  -moz-animation: linear 1.2s light infinite;
  -o-animation: linear 1.2s light infinite;
  animation: linear 1.2s light infinite;
  }
  @-webkit-keyframes light{
  0%   { color: #ddd; text-shadow: 0px -1px 0px #000; }
  50%   { color: #fff; text-shadow: 0px -1px 0px #444, 0px 0px 5px #ffd, 0px 0px 8px #fff; }
  100% { color: #ddd; text-shadow: 0px -1px 0px #000; }
  }
  @-moz-keyframes light{
  0%   { color: #ddd; text-shadow: 0px -1px 0px #000; }
  50%   { color: #fff; text-shadow: 0px -1px 0px #444, 0px 0px 5px #ffd, 0px 0px 8px #fff; }
  100% { color: #ddd; text-shadow: 0px -1px 0px #000; }
  }
  @-o-keyframes light{
  0%   { color: #ddd; text-shadow: 0px -1px 0px #000; }
  50%   { color: #fff; text-shadow: 0px -1px 0px #444, 0px 0px 5px #ffd, 0px 0px 8px #fff; }
  100% { color: #ddd; text-shadow: 0px -1px 0px #000; }
  }
  @keyframes light{
  0%   { color: #ddd; text-shadow: 0px -1px 0px #000; }
  50%   { color: #fff; text-shadow: 0px -1px 0px #444, 0px 0px 5px #ffd, 0px 0px 8px #fff; }
  100% { color: #ddd; text-shadow: 0px -1px 0px #000; }
  }
  a.tr:active{
  color: #fff;
  text-shadow: 0px -1px 0px #444,0px 0px 5px #ffd,0px 0px 8px #fff;
  box-shadow: 0px 1px 0px #666,0px 2px 0px #444,0px 2px 2px rgba(0, 0, 0, .9);
  -webkit-transform: translateY(3px);
  -moz-transform: translateY(3px);
  -o-transform: translateY(3px);
  transform: translateY(3px);
  -webkit-animation: none;
  -moz-animation: none;
  -o-animation: none;
  animation: none;
  }
#sound{
    width: 250px;
    margin-top:-10px;
    margin-left:300px;
    transform:rotate(-20deg);
    position: absolute;
}
#so:hover{
  transform: scale(1.7, 1.7);
}
#r1{
  background-color: Transparent;
  border: none;
  cursor:pointer;
  overflow: hidden;
  outline:none;
  width: 100px;
  height: 140px;
  z-index: 400;
  position: absolute;
  top:25px;
  left:380px;
}
#PS1{
  background-position: 5px 5px;
  position:absolute;
  left:840px;
  top:-0px;
  transform: rotate(18deg);
  width: 500px;
  }
#ps:hover{
  transform: scale(2, 2);
}
#r2{
background-color: Transparent;
border: none;
cursor:pointer;
overflow: hidden;
outline:none;
width: 180px;
height: 160px;
z-index: 400;
position: absolute;
top:30px;
left:1050px;
}

#r3{
  background-color: Transparent;
  border: none;
  cursor:pointer;
  overflow: hidden;
  outline:none;
  width: 180px;
  height: 160px;
  z-index: 400;
  position: absolute;
  top:390px;
  left:94px;
}
#sidi{
  background-position: 5px 5px;
  position: absolute;
  width: 300px;
  top:365px;
  left:55px;
  transform: rotate(18deg);
}
#kres:hover{
  transform: scale(2, 2);
}
#VR{
  background-position: 5px 5px;
  position:absolute;
  left:650px;
  width: 250px;
}
#vr:hover{
  transform: scale(2, 2);
}
#r4{
  background-color: Transparent;
  border: none;
  cursor:pointer;
  overflow: hidden;
  outline:none;
  left:650px;
  width: 250px;
  height: 160px;
  z-index: 400;
  position: absolute;
}
#KLA{
  position: absolute;
  top:  310px;
  left: 320px;
  width: 550px;
}
#KLAVA:hover{
  transform: scale(2.2, 2.2);
}
#r5{
  background-color: Transparent;
  border: none;
  cursor:pointer;
  overflow: hidden;
  outline:none;
  top:  470px;
  left: 320px;
  width: 550px;
  height: 190px;
  z-index: 4000;
  position: absolute;
}

#MOUSE{
  position: absolute;
  top: 430px;
  left: 920px;
  width: 250px;
  transform: rotate(-10deg);
}
#mouse:hover{
  transform: scale(2.2, 2.2);
}
#r6{
  background-color: Transparent;
  border: none;
  cursor:pointer;
  overflow: hidden;
  outline:none;
  top: 430px;
  left: 960px;
  width: 170px;
  height: 250px;
  z-index: 4000;
  position: absolute;
}

#PLANNER{
position: absolute;
top: 770px;
left: 840px;
width: 270px;
}
#planner:hover{
  transform: scale(2.2, 2.2);
}
#r7{
  background-color: Transparent;
  border: none;
  cursor:pointer;
  overflow: hidden;
  outline:none;
  top: 770px;
  left: 840px;
  width: 270px;
  height: 100px;
  z-index: 4000;
  position: absolute;
}

#LODKA{
  position: absolute;
  top: 1480px;
  left: 910px;
  width: 250px;
  }
  #lodka:hover{
    transform: scale(2.2, 2.2);
  }
  #r8{
    background-color: Transparent;
    border: none;
    cursor:pointer;
    overflow: hidden;
    outline:none;
    top: 1480px;
    left: 910px;
    width: 250px;
    height: 100px;
    z-index: 4000;
    position: absolute;
  }

  #ECSC{
    position: absolute;
    top: 1900px;
    left: 630px;
    width: 300px;
    }
    #ecsc:hover{
      transform: scale(2.2, 2.2);
    }
    #r9{
      background-color: Transparent;
      border: none;
      cursor:pointer;
      overflow: hidden;
      outline:none;
      top: 1910px;
    left: 660px;
    width: 260px;
      height: 170px;
      z-index: 4000;
      position: absolute;
    }

    #BAGI{
      position: absolute;
      top: 1630px;
      left: 130px;
      width: 250px;
      }
      #bagi:hover{
        transform: scale(2.2, 2.2);
      }
#r10{
    background-color: Transparent;
     position: absolute;
    border: none;
    cursor:pointer;
    overflow: hidden;
    outline:none;
    top: 1630px;
   left: 130px;
    width: 240px;
    height: 170px;
    z-index: 4100;       
}




#RDFLH{
  position: absolute;
  top: 970px;
  left: 760px;
  width: 240px;
  }
  #rdflh:hover{
    transform: scale(2.2, 2.2);
  }
  #r11{
    background-color: Transparent;
    border: none;
    cursor:pointer;
    overflow: hidden;
    outline:none;
    top: 970px;
    left: 760px;
    width: 240px;
    height: 120px;
    z-index: 4000;
    position: absolute;
}

#KVADR{
  position: absolute;
  top: 1170px;
  left: 1060px;
  width: 100px;
  }
  #kvadr:hover{
    transform: scale(2.2, 2.2);
  }
  #r12{
    background-color: Transparent;
    border: none;
    cursor:pointer;
    overflow: hidden;
    outline:none;
    top: 1170px;
    left: 1060px;
    width: 100px;
    height: 100px;
    z-index: 4000;
    position: absolute;
}



a.SOS{
  display: block;
  font-size: 1.1em;
  width:90px;
  text-decoration:none;
  text-align:center;
  font: bold 14px arial;
  text-transform: uppercase;
  padding: 10px 15px;
  margin: 20px 510px;
  color: #ccc;
  background-color: #555;
  background-image: linear-gradient(top, #888 0%, #555 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0, #888), color-stop(1, #555));
  background-image: -moz-linear-gradient(top, #888 0%, #555 100%);
  background-image: -o-linear-gradient(top, #888 0%, #555 100%);
  border: none;
  border-radius: 3px;
  text-shadow: 0px -1px 0px #000;
  box-shadow: 0px 1px 0px #666,0px 5px 0px #444,0px 6px 6px rgba(0, 0, 0, .6);
  -webkit-transition: ease .15s all;
  -moz-transition: ease .15s all;
  -o-transition: ease .15s all;
  transition: ease .15s all;
  -webkit-animation: none;
   -moz-animation: none;
   -o-animation: none;
    animation: none;
  }
  a.SOS:hover, a.SOS:focus{
  -webkit-animation: linear 1.2s light infinite;
  -moz-animation: linear 1.2s light infinite;
  -o-animation: linear 1.2s light infinite;
  animation: linear 1.2s light infinite;
  }
  @-webkit-keyframes light{
  0%   { color: #ddd; text-shadow: 0px -1px 0px #000; }
  50%   { color: #fff; text-shadow: 0px -1px 0px #444, 0px 0px 5px #ffd, 0px 0px 8px #fff; }
  100% { color: #ddd; text-shadow: 0px -1px 0px #000; }
  }
  @-moz-keyframes light{
  0%   { color: #ddd; text-shadow: 0px -1px 0px #000; }
  50%   { color: #fff; text-shadow: 0px -1px 0px #444, 0px 0px 5px #ffd, 0px 0px 8px #fff; }
  100% { color: #ddd; text-shadow: 0px -1px 0px #000; }
  }
  @-o-keyframes light{
  0%   { color: #ddd; text-shadow: 0px -1px 0px #000; }
  50%   { color: #fff; text-shadow: 0px -1px 0px #444, 0px 0px 5px #ffd, 0px 0px 8px #fff; }
  100% { color: #ddd; text-shadow: 0px -1px 0px #000; }
  }
  @keyframes light{
  0%   { color: #ddd; text-shadow: 0px -1px 0px #000; }
  50%   { color: #fff; text-shadow: 0px -1px 0px #444, 0px 0px 5px #ffd, 0px 0px 8px #fff; }
  100% { color: #ddd; text-shadow: 0px -1px 0px #000; }
  }
  a.SOS:active{
  color: #fff;
  text-shadow: 0px -1px 0px #444,0px 0px 5px #ffd,0px 0px 8px #fff;
  box-shadow: 0px 1px 0px #666,0px 2px 0px #444,0px 2px 2px rgba(0, 0, 0, .9);
  -webkit-transform: translateY(3px);
  -moz-transform: translateY(3px);
  -o-transform: translateY(3px);
  transform: translateY(3px);
  -webkit-animation: none;
  -moz-animation: none;
  -o-animation: none;
  animation: none;
  }


  #sos{
    position: absolute;
    left: 800px;
    top:290px;
    width: 200px;
    display: none;
    z-index: 10000;
  }
#OBRAZ{
  position: absolute;
  left: 500px;
  top: 200px;
  width: 300px;
  height: 700px;
  z-index: 9999;
  display: none;
}
#OBRAZBUT{
  position: absolute;
  left: 500px;
  top: 310px;
  width: 300px;
  height: 100px;
  z-index: 10000;
  display: none;
  border: none;
cursor:pointer;
overflow: hidden;
outline:none;
background-color: Transparent;
}
#obraz:hover{
  transform: scale(2.2, 2.2);
}
</style>
</head>

<body > 

<div id="skla" class="djrheu"> 
    <div id="vkla" class="dyenhb">
       <a href="http://buyeasy.by/redirect/cpa/o/pjdrqujaxkrr4q4pqsewqlw10v0bbvcf/"><img src="img/klava.png"  class="kl" id="kl1"> </a>  <br><br><br><br>
       <a id="tr" class="tr"  href="#">1</a>
       <a id="tr1" class="tr" href="#" >2</a>
       <a id="tr2" class="tr" href="#" >3</a>
    </div>
</div>
<button id="r"></button>
<img src="img/Klava.png" id="Kla"  class="ikla" >

<div id="ssou" class="djrheu"> 
    <div id="vsou" class="dyenhb">
    <a href="http://buyeasy.by/redirect/cpa/o/pjex8wufup3ih92d1uybre2cpvcf9x6b/"><img src="img/sound.png"  class="kl" id="so"> </a>   <br><br><br><br>
    <a id="so1" class="tr"  href="#">1</a>
    <a id="so2" class="tr" href="#" >2</a>
    <a id="so3" class="tr" href="#" >3</a>
    </div>
</div>
<button id="r1"></button>
<img src="img/sound.png" id="sound" class="isound" >




<div id="sps" class="djrheu"> 
   <div id="vps" class="dyenhb">
   <a href="http://buyeasy.by/redirect/cpa/o/pjdq1el2wnqeio4di7pv4otwsxam1bns/"><img src="img/ps_1.png"  class="kl" id="ps"> </a>  <br><br><br><br><br>
   <a id="ps1" class="tr"  href="#">1</a>
   <a id="ps2" class="tr" href="#" >2</a>
   <a id="ps3" class="tr" href="#" >3</a>
    </div>
</div>
<button id="r2"></button>
<img src="img/PS1.png" id="PS1"    class="ips1">



<div id="skres" class="djrheu"> 
    <div id="vkres" class="dyenhb">
    <a href="http://buyeasy.by/redirect/cpa/o/pjdq1el2wnqeio4di7pv4otwsxam1bns/"><img src="img/kres3.png"  class="kl" id="kres"> </a>  <br><br><br><br><br><br><br><br>
    <a id="kres1" class="tr"  href="#">1</a>
    <a id="kres2" class="tr" href="#" >2</a>
    <a id="kres3" class="tr" href="#" >3</a>
    </div>
</div>
 <button id="r3"></button>
<img src="img/Кресло.png" id="sidi" class="isidi">



<div id="svr" class="djrheu"> 
    <div id="vvr" class="dyenhb">
    <a href="http://buyeasy.by/redirect/cpa/o/pjdqy7qy1p0vmy7rd59x0k0ned0xuzzo/"><img src="img/VR-Pro.png"  class="kl" id="vr"> </a>  <br><br><br><br><br>><br><br>><br><br>
    <a id="vr1" class="tr"  href="#">1</a>
    <a id="vr2" class="tr" href="#" >2</a>
    <a id="vr3" class="tr" href="#" >3</a>
    </div>
</div>
 <button id="r4"></button>
<img src="img/VR-Pro.png" id="VR" class="ivr" >



<div id="sKL" class="djrheu">
    <div id="vKL" class="dyenhb">
        <a href="http://buyeasy.by/redirect/cpa/o/pjqe5y9tlmstv0h420daotf03a7kr3t1/"><img src="img/KLAVA_.png"  class="kl" id="KLAVA"></a>   <br><br><br><br><br><br><br><br>
        <a id="KL1" class="tr" href="#">1</a>
        <a id="KL2" class="tr" href="#">2</a>
        <a id="KL3" class="tr" href="#">3</a>
    </div>
</div>
<button id="r5"></button>
<img src="img/KLAVA_.png" id="KLA" class="ivr" >


<div id="smouse" class="djrheu">
    <div id="vmouse" class="dyenhb">
        <a href="http://buyeasy.by/redirect/cpa/o/pjqfxwwvqh9tqvl5hjd7liv2519fq4zq/"><img src="img/mouse.png"  class="kl" id="mouse"></a>   <br><br><br><br><br><br><br><br>
        <a id="mouse1" class="tr" href="#">1</a>
        <a id="mouse2" class="tr" href="#">2</a>
        <a id="mouse3" class="tr" href="#">3</a>
    </div>
</div>
<button id="r6"></button>
<img src="img/mouse.png" id="MOUSE" class="imouse" >



<div id="splanner" class="djrheu">
    <div id="vplanner" class="dyenhb">
        <a href="http://buyeasy.by/redirect/cpa/o/pjqmrq28bsquccl3itwi7m0ptolaax57/"><img src="img/PLANNER.png"  class="kl" id="planner"></a>   <br><br><br><br><br><br><br><br>
        <a id="planner1" class="tr" href="#">1</a>
        <a id="planner2" class="tr" href="#">2</a>
        <a id="planner3" class="tr" href="#">3</a>
    </div>
</div>
<button id="r7"></button>
<img src="img/PLANNER.png" id="PLANNER" class="imouse" >



<div id="slodka" class="djrheu">
    <div id="vlodka" class="dyenhb">
        <a href="http://buyeasy.by/redirect/cpa/o/pjqms4u83sjy3mxx1gn4nqzyt1rtjgwb/"><img src="img/LODKA.png"  class="kl" id="lodka"></a>   <br><br><br><br><br><br><br><br>
        <a id="lodka1" class="tr" href="#">1</a>
        <a id="lodka2" class="tr" href="#">2</a>
        <a id="lodka3" class="tr" href="#">3</a>
    </div>
</div>
<button id="r8"></button>
<img src="img/LODKA.png" id="LODKA" class="ilodka" >


<div id="secsc" class="djrheu">
    <div id="vecsc" class="dyenhb">
        <a href="http://buyeasy.by/redirect/cpa/o/pjqmsxhkl9g5rj1xpooeu8lpfbfokoa8/"><img src="img/ECSC.png"  class="kl" id="ecsc"></a>   <br><br><br><br><br><br><br><br>
        <a id="ecsc1" class="tr" href="#">1</a>
        <a id="ecsc2" class="tr" href="#">2</a>
        <a id="ecsc3" class="tr" href="#">3</a>
    </div>
</div>
<button id="r9"></button>
<img src="img/ECSC.png" id="ECSC" class="iecsc" >

<div id="sbagi" class="djrheu">
    <div id="vbagi" class="dyenhb">
        <a href="http://buyeasy.by/redirect/cpa/o/pjqmsg270slizowy8kgxgrs0cx7bbtgj/"><img src="img/BAGI.png"  class="kl" id="bagi"></a>   <br><br><br><br><br><br><br><br>
        <a id="bagi1" class="tr" href="#">1</a>
        <a id="bagi2" class="tr" href="#">2</a>
        <a id="bagi3" class="tr" href="#">3</a>
    </div>
</div>
<button id="r10"></button>
<img src="img/BAGI.png" id="BAGI" class="ibagi" >

<div id="srdflh" class="djrheu">
    <div id="vrdflh" class="dyenhb">
        <a href="http://buyeasy.by/redirect/cpa/o/pjqmqnalry1rsayd64rs2xft1s31l0n1/"><img src="img/RDFLH.png"  class="kl" id="rdflh"></a>   <br><br><br><br><br><br><br><br>
        <a id="rdflh1" class="tr" href="#">1</a>
        <a id="rdflh2" class="tr" href="#">2</a>
        <a id="rdflh3" class="tr" href="#">3</a>
    </div>
</div>
<button id="r11"></button>
<img src="img/RDFLH.png" id="RDFLH" class="irdflh" >




<div id="skvadr" class="djrheu">
    <div id="vkvadr" class="dyenhb">
        <a href="http://buyeasy.by/redirect/cpa/o/pjqmr7ufhaar68mjng5i52uyi5rawhaf/"><img src="img/KVADR.png"  class="kl" id="kvadr"></a>   <br><br><br><br><br><br><br><br>
        <a id="kvadr1" class="tr" href="#">1</a>
        <a id="kvadr2" class="tr" href="#">2</a>
        <a id="kvadr3" class="tr" href="#">3</a>
    </div>
</div>
<button id="r12"></button>
<img src="img/KVADR.png" id="KVADR" class="ikvadr" >




<div id="sobraz" class="djrheu">
    <div id="vobraz" class="dyenhb">
        <a href="http://buyeasy.by/redirect/cpa/o/pjssxijhaddn9aae6hacbju62dmnszqt/"><img src="img/fhoto1.png"  class="kl" id="obraz"></a>   <br><br><br><br><br><br><br><br>
        <a id="fhoto1" class="tr" href="#">Кликни что бы посмотреть 1 фото</a>
        <a id="fhoto2" class="tr" href="#">Кликни что бы посмотреть 2 фото</a>
        <a id="fhoto3" class="tr" href="#">Кликни что бы посмотреть 3 фото</a>
    </div>
</div>
,<button id="OBRAZBUT"></button>
<img id="OBRAZ" class="OBRAZ" src="img/obraz.png" >
<img id="sos" class="sos" src="img/sos.png" >
<a href="#" id="SOS" class="SOS">Как здесь заказывать</a>

<script type="text/javascript" src="$.js" ></script>
</body>

</html>
