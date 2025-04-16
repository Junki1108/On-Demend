<style>
#tal1 {
    background-color: #00ff99;
    width: 350px;
    height: 350px;
    border-radius: 100px 100px;
    box-shadow: darkgreen 10px 10px 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    float: left;
    margin-left: 10px;
}
#tal1 > img {
    width: 70%;
    height: 70%;
    border-radius: 75px 75px;
    animation: rotate1 2s linear infinite;
    transition: 0.5s;
}
#tal2 {
    background-color: #FF3300;
    width: 350px;
    height: 350px;
    border-radius: 100px 100px;
    box-shadow: darkred 10px 10px 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    float: left;
    margin-left: 10px;
}
#tal2 > img {
    width: 70%;
    height: 70%;
    border-radius: 75px 75px;
    animation: rotate2 1s linear infinite;
    transition: 0.5s;
}
@keyframes rotate1 {
    from {transform: rotate(0deg);}
    50% {transform: rotate(180deg);}
    to {transform: rotate(360deg);}
}
@keyframes rotate2 {
    from {transform: rotate(0deg);}
    50% {transform: rotate(-180deg);}
    to {transform: rotate(-360deg);}
}
#tal1 > img:hover {width: 85%; height: 85%;}
#tal1 > img:active {animation: rotate1 0.5s linear infinite;}
#tal2 > img:hover {width: 85%; height: 85%;}
#tal2 > img:active {animation: rotate2 0.002ms linear infinite;}
</style>
<div id="tal1"><img src="../talmo.jpeg"></div>
<div id="tal2"><img src="../pig.jpeg"></div>