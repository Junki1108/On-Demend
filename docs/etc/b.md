# 이상한 사람들
<script>
  const password = prompt("인증이 필요합니다. 비밀번호를 입력하세요.");

  if (password !== "flag1235") {
    alert("비밀번호가 틀렸습니다. 당신은 접근할 권한이 없습니다.");
    window.location.href = "/On-Demend/etc/403/";
  }
</script>

<style>
.squ { width: 300px; height: 300px; display: flex; justify-content: center; align-items: center; float: left; border-radius: 100px 100px; margin-right: 20px;}
.squ > img {width: 70%; height: 70%; border-radius: 75px 75px; transition: 0.5s;}
#box1 {background-color: #ED4545; box-shadow: red 5px 10px 20px;}
#box1 > img {animation: rotate1 2s linear infinite;}
#box2 {background-color: #ED7745; box-shadow: orange 10px 10px 20px;}
#box2 > img {animation: rotate2 3s linear infinite;}
#box3 {background-color: #EDCE45; box-shadow: yellow 10px 10px 20px;}
#box3 > img {animation: rotate3 2s linear infinite;}
#box4 {background-color: #5EED45; box-shadow: white 10px 10px 20px; animation: special4 10s linear infinite;}
#box4 > img {animation: rotate4 2s ease infinite;}
@keyframes rotate1 {
    from {transform: rotate(0deg);}
    50% {transform: rotate(180deg);}
    to {transform: rotate(360deg);}}
@keyframes rotate2 {
    from {transform: rotate(0deg);}
    50% {transform: rotate(360deg);}
    to {transform: rotate(0deg);}}
@keyframes rotate3 {
    from {transform: rotate(0deg);}
    80% {transform: rotate(-180deg);}
    to {transform: rotate(360deg);}}
@keyframes rotate4 {
    from {transform: rotate(0deg);}
    50% {transform: rotate(180deg);}
    to {transform: rotate(360deg);}}
@keyframes special4 {
    0% {background-color: red;}
    12% {background-color: orange;}
    23% {background-color: yellow;}
    34% {background-color: lime;}
    45% {background-color: green;}
    56% {background-color: lightblue;}
    67% {background-color: blue;}
    78% {background-color: purple;}
    89% {background-color: pink;}
    100% {background-color: red;}
}
#box1 > img:hover {width: 85%; height: 85%;}
#box1 > img:active {animation: rotate1 0.5s linear infinite;}
#box2 > img:hover {width: 85%; height: 85%;}
#box2 > img:active {animation: rotate2 0.05ms linear infinite;}
#box3 > img:hover {width: 85%; height: 85%;}
#box3 > img:active {animation: rotate3 0.75ms linear infinite;}
#box4 > img:hover {width: 85%; height: 85%;}
#box4 > img:active {animation: rotate3 0.75ms ease infinite;}
</style>
<div id="box1" class="squ"><img src="../talmo.jpeg"></div>
<div id="box2" class="squ"><img src="../pig.jpeg"></div>
<div id="box3" class="squ"><img src="../150cm.png"></div>
<div id="box4" class="squ"><img src="../amin.png"></div>