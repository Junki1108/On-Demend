<style>
#tal {
    background-color: #00ff99;
    width: 350px;
    height: 350px;
    border-radius: 100px 100px;
    box-shadow: darkgreen 10px 10px 20px;
    display: flex;
    justify-content: center;
    align-items: center;
}
#tal > img {
    width: 70%;
    height: 70%;
    border-radius: 75px 75px;
    animation: rotate 2s linear infinite;
    transition: 0.5s;
}
@keyframes rotate {
    from {transform: rotate(0deg);}
    50% {transform: rotate(180deg);}
    to {transform: rotate(360deg);}
}
#tal > img:hover {width: 85%; height: 85%;}
#tal > img:active {animation: rotate 0.5s linear infinite;}
</style>
<div id="tal"><img src="../talmo.jpeg"></div>