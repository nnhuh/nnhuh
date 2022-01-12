var tik = setInterval(() => {
  var lyf = document.getElementById('digit')
  lyf.classList.toggle("digit");
  if (lyf.innerText == 0) {
    document.getElementById('container').classList.toggle("containeroverlay")
    window.location="./MyBirthday/MyBirthday.html";
    clearInterval(tik)
  } else {
    lyf.innerText -= 1
  }
  lyf.classList.toggle("digit");
}, 1000)
https://scontent.fsgn7-1.fna.fbcdn.net/v/t39.30808-6/271734354_642099523907537_3516569941826122799_n.jpg?_nc_cat=108&cb=c578a115-c1c39920&ccb=1-5&_nc_sid=0debeb&_nc_ohc=eUaZUvEymsIAX9Ez5dk&_nc_ht=scontent.fsgn7-1.fna&oh=00_AT-_lZVpJp_GRXnClV-3KPOwgznZUrvk8v7ZomBhDF4fZA&oe=61E3DFAB
<html lang="vi"
    __fvdsurfcanyoninserted="1"
    class="
        clickberry-extension
        clickberry-extension-standalone
        clickberry-extension
        clickberry-extension-standalone
        clickberry-extension
        clickberry-extension-standalone
    "
>
    <head>
        <meta charset="UTF-8" />
        <link rel="shortcut icon" type="image/png" href="./birthdayCake.png"/>
        <title>Happy Birthday</title>
        <link rel="stylesheet" href="./style.css">
        <script>
            window.open = function () {};
            window.print = function () {};
            // Support hover state for mobile.
            if (false) {
                window.ontouchstart = function () {};
            }
        </script>
        <script
            type="text/javascript"
            src="chrome-extension://bfbmjmiodbnnpllbbbfblcplfjjepjdn/js/injected.js"
        ></script>
        <meta content="clickberry-extension-here" />
    </head>

    <body>
        <link
            href="https://fonts.googleapis.com/css?family=Wendy+One"
            rel="stylesheet"
            type="text/css"
        />
        <div class="pyro">
            <div class="before">
                
            </div>
            <div class="after">

            </div>
            <div class="container">
                <!-- 2. Dòng chữ Happy Birthday
                Nếu bạn muốn thêm chữ vào thì phải thay đổi css tương ứng cho nó -->
                <div class="balloon">
                    <div><span>H</span></div>
                    <div><span>A</span></div>
                    <div><span>P</span></div>
                    <div><span>P</span></div>
                    <div><span>Y</span></div>
                    <div><span>B</span></div>
                    <div><span>I</span></div>
                    <div><span>R</span></div>
                    <div><span>T</span></div>
                    <div><span>H</span></div>
                    <div><span>D</span></div>
                    <div><span>A</span></div>
                    <div><span>Y</span></div>
                </div>
                <div class="avatar">
                    <!-- https://scontent.fsgn7-1.fna.fbcdn.net/v/t39.30808-6/271734354_642099523907537_3516569941826122799_n.jpg?_nc_cat=108&cb=c578a115-c1c39920&ccb=1-5&_nc_sid=0debeb&_nc_ohc=eUaZUvEymsIAX9Ez5dk&_nc_ht=scontent.fsgn7-1.fna&oh=00_AT-_lZVpJp_GRXnClV-3KPOwgznZUrvk8v7ZomBhDF4fZA&oe=61E3DFAB
 -->
                    <img src="./MyAvatar.jpg" alt="" class="avatar__img" onclick="showMessage()" />
                    <!--Bùi Thùy Trinh -->
                    <h1 onclick="showMessage()" class="avatar__title">Thùy Trinhn</h1>
                </div>
                
                <!-- https://www.nhaccuatui.com/bai-hat/birthday-katy-perry.XbTTKe0zHR23.html -->
                <!-- <audio id="player" autoplay loop>
                    <source src="./music.mp3" type="audio/mp3">
                </audio> -->
            </div>
        </div>
        <script>
            if (document.location.search.match(/type=embed/gi)) {
                window.parent.postMessage("resize", "*");
            }
            function showMessage() {
                //Xin gửi lời chúc mừng sinh nhật thân thương nhất tới một trong những công dân xinh đẹp, mỹ miều, kiêu sa, yêu kiều nhất trên quả đất này. Chúc bạn thân của tui luôn luôn "tươi trẻ, tính tình mát mẻ, lúc nào cũng vui vẻ và cuộc đời luôn suôn sẻ" nhé!
Happy Birthday!
({
                    title: "Lời nhắn", // Tiêu đề của popup
                    text: "Xin gửi lời chúc mừng sinh nhật thân thương nhất tới một trong những công dân xinh đẹp, mỹ miều, kiêu sa, yêu kiều nhất trên quả đất này. Chúc bạn thân của tui luôn luôn "tươi trẻ, tính tình mát mẻ, lúc nào cũng vui vẻ và cuộc đời luôn suôn sẻ" nhé!
Happy Birthday!
: {
                        text: "❤️️",
                    },
                });
            }
        </script>
        <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
    </body>
</html>
https://github.com/ngoctienTNT/MyBirthday/blob/main/MyBirthday/birthdayCake.png?raw=true
@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');

body {
    background-image: -webkit-gradient(
        radial,
        50% 50%,
        0,
        50% 50%,
        100,
        color-stop(0%, #374566),
        color-stop(100%, #010203)
    );
    background-image: -webkit-radial-gradient(#374566, #010203);
    background-image: -moz-radial-gradient(#374566, #010203);
    background-image: -o-radial-gradient(#374566, #010203);
    background-image: radial-gradient(#374566, #010203);
    font-family: 'Lobster', cursive;
}
span {
    text-transform: uppercase;
}
.container {
    width: 800px;
    height: 100%;
    padding: 10px;
    margin: 0 auto;
    position: relative;
}
.balloon {
    width: 738px;
    margin: 0 auto;
    padding-top: 30px;
    position: relative;
    font-family: "Wendy One", sans-serif;
}
.balloon > div {
    width: 104px;
    height: 140px;
    background: rgba(182, 15, 97, 0.9);
    border-radius: 0;
    border-radius: 80% 80% 80% 80%;
    margin: 0 auto;
    position: absolute;
    padding: 10px;
    box-shadow: inset 17px 7px 10px rgba(182, 15, 97, 0.9);
    -webkit-transform-origin: bottom center;
}
.balloon > div:nth-child(1) {
    background: rgba(182, 15, 97, 0.9);
    left: 60px;
    box-shadow: inset 10px 10px 10px rgba(135, 11, 72, 0.9);
    -webkit-animation: balloon1 6s ease-in-out infinite;
    -moz-animation: balloon1 6s ease-in-out infinite;
    -o-animation: balloon1 6s ease-in-out infinite;
    animation: balloon1 6s ease-in-out infinite;
}
.balloon > div:nth-child(1):before {
    color: rgba(182, 15, 97, 0.9);
}
.balloon > div:nth-child(2) {
    background: rgba(242, 112, 45, 0.9);
    left: 180px;
    box-shadow: inset 10px 10px 10px rgba(222, 85, 14, 0.9);
    -webkit-animation: balloon2 6s ease-in-out infinite;
    -moz-animation: balloon2 6s ease-in-out infinite;
    -o-animation: balloon2 6s ease-in-out infinite;
    animation: balloon2 6s ease-in-out infinite;
}
.balloon > div:nth-child(2):before {
    color: rgba(242, 112, 45, 0.9);
}
.balloon > div:nth-child(3) {
    background: rgba(45, 181, 167, 0.9);
    left: 300px;
    box-shadow: inset 10px 10px 10px rgba(35, 140, 129, 0.9);
    -webkit-animation: balloon4 6s ease-in-out infinite;
    -moz-animation: balloon4 6s ease-in-out infinite;
    -o-animation: balloon4 6s ease-in-out infinite;
    animation: balloon4 6s ease-in-out infinite;
}
.balloon > div:nth-child(3):before {
    color: rgba(45, 181, 167, 0.9);
}
.balloon > div:nth-child(4) {
    background: rgba(190, 61, 244, 0.9);
    left: 420px;
    box-shadow: inset 10px 10px 10px rgba(173, 14, 240, 0.9);
    -webkit-animation: balloon1 5s ease-in-out infinite;
    -moz-animation: balloon1 5s ease-in-out infinite;
    -o-animation: balloon1 5s ease-in-out infinite;
    animation: balloon1 5s ease-in-out infinite;
}
.balloon > div:nth-child(4):before {
    color: rgba(190, 61, 244, 0.9);
}
.balloon > div:nth-child(5) {
    background: rgba(180, 224, 67, 0.9);
    left: 540px;
    box-shadow: inset 10px 10px 10px rgba(158, 206, 34, 0.9);
    -webkit-animation: balloon3 5s ease-in-out infinite;
    -moz-animation: balloon3 5s ease-in-out infinite;
    -o-animation: balloon3 5s ease-in-out infinite;
    animation: balloon3 5s ease-in-out infinite;
}
.balloon > div:nth-child(5):before {
    color: rgba(180, 224, 67, 0.9);
}
.balloon > div:nth-child(6) {
    background: rgba(242, 194, 58, 0.9);
    left: -150px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(234, 177, 15, 0.9);
    -webkit-animation: balloon4 3s ease-in-out infinite;
    -moz-animation: balloon4 3s ease-in-out infinite;
    -o-animation: balloon4 3s ease-in-out infinite;
    animation: balloon4 3s ease-in-out infinite;
}
.balloon > div:nth-child(6):before {
    color: rgba(242, 194, 58, 0.9);
}

/* ================= 7 ====================== */
.balloon > div:nth-child(7) {
    background: rgba(45, 181, 167, 0.9);
    left: -30px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(45, 181, 167, 0.9);
    -webkit-animation: balloon3 5s ease-in-out infinite;
    -moz-animation: balloon3 5s ease-in-out infinite;
    -o-animation: balloon3 5s ease-in-out infinite;
    animation: balloon3 5s ease-in-out infinite;
}
.balloon > div:nth-child(7):before {
    color: rgba(45, 181, 167, 0.9);
}

/* ================= 8 ====================== */
.balloon > div:nth-child(8) {
    background: rgba(242, 58, 165, 0.9);
    left: 90px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(242, 58, 165, 0.9);
    -webkit-animation: balloon2 3s ease-in-out infinite;
    -moz-animation: balloon2 3s ease-in-out infinite;
    -o-animation: balloon2 3s ease-in-out infinite;
    animation: balloon2 3s ease-in-out infinite;
}
.balloon > div:nth-child(8):before {
    color: rgba(242, 58, 165, 0.9);
}

/* ================= 9 ====================== */
.balloon > div:nth-child(9) {
    background: rgba(182, 15, 97, 0.9);
    left: 210px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(182, 15, 97, 0.9);
    -webkit-animation: balloon4 5s ease-in-out infinite;
    -moz-animation: balloon4 5s ease-in-out infinite;
    -o-animation: balloon4 5s ease-in-out infinite;
    animation: balloon4 5s ease-in-out infinite;
}
.balloon > div:nth-child(9):before {
    color: rgba(182, 15, 97, 0.9);
}

/* ================= 10 ====================== */
.balloon > div:nth-child(10) {
    background: rgba(242, 194, 58, 0.9);
    left: 330px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(234, 177, 15, 0.9);
    -webkit-animation: balloon1 6s ease-in-out infinite;
    -moz-animation: balloon1 6s ease-in-out infinite;
    -o-animation: balloon1 6s ease-in-out infinite;
    animation: balloon1 6s ease-in-out infinite;
}
.balloon > div:nth-child(10):before {
    color: rgba(242, 194, 58, 0.9);
}

/* ================= 11 ====================== */
.balloon > div:nth-child(11) {
    background: rgba(234, 15, 15, 0.9);
    left: 450px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(234, 15, 15, 0.9);
    -webkit-animation: balloon2 4s ease-in-out infinite;
    -moz-animation: balloon2 4s ease-in-out infinite;
    -o-animation: balloon2 4s ease-in-out infinite;
    animation: balloon2 4s ease-in-out infinite;
}
.balloon > div:nth-child(11):before {
    color: rgba(234, 15, 15, 0.9);
}

/* ================= 12 ====================== */
.balloon > div:nth-child(12) {
    background: rgba(64, 241, 28, 0.9);
    left: 580px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(64, 241, 28, 0.9);
    -webkit-animation: balloon1 3s ease-in-out infinite;
    -moz-animation: balloon1 3s ease-in-out infinite;
    -o-animation: balloon1 3s ease-in-out infinite;
    animation: balloon1 3s ease-in-out infinite;
}
.balloon > div:nth-child(12):before {
    color: rgba(64, 241, 28, 0.9);
}

/* ================= 13 ====================== */
.balloon > div:nth-child(13) {
    background: rgba(15, 219, 234, 0.9);
    left: 700px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(15, 219, 234, 0.9);
    -webkit-animation: balloon2 6s ease-in-out infinite;
    -moz-animation: balloon2 6s ease-in-out infinite;
    -o-animation: balloon2 6s ease-in-out infinite;
    animation: balloon2 6s ease-in-out infinite;
}
.balloon > div:nth-child(13):before {
    color: rgba(15, 219, 234, 0.9);
}

/* Avatar  */
.avatar {
    cursor: pointer;
    position: absolute;
    top: 50%;
    left: calc(50% - 100px);
}

.avatar__img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    border: 5px solid rgba(234, 15, 150, 0.9);
    box-shadow: inset 10px 10px 10px rgba(15, 219, 234, 0.9);
    -webkit-animation: balloon1 6s ease-in-out infinite;
    -moz-animation: balloon1 6s ease-in-out infinite;
    -o-animation: balloon1 6s ease-in-out infinite;
    animation: balloon1 6s ease-in-out infinite;
}

.avatar__title {
    cursor: pointer;
    margin-top: -100px;
    -webkit-animation: balloon1 4s ease-in-out infinite;
    -moz-animation: balloon1 4s ease-in-out infinite;
    -o-animation: balloon1 4s ease-in-out infinite;
    animation: balloon1 4s ease-in-out infinite;
}
.balloon > div:before {
    color: rgba(182, 15, 97, 0.9);
    position: absolute;
    bottom: -11px;
    left: 52px;
    content: "▲";
    font-size: 1em;
}
span {
    font-size: 4.8em;
    color: white;
    position: relative;
    top: 30px;
    left: 50%;
    margin-left: -27px;
}
/*BALLOON 1 4*/
@-webkit-keyframes balloon1 {
    0%,
    100% {
        -webkit-transform: translateY(0) rotate(-6deg);
    }
    50% {
        -webkit-transform: translateY(-20px) rotate(8deg);
    }
}
@-moz-keyframes balloon1 {
    0%,
    100% {
        -moz-transform: translateY(0) rotate(-6deg);
    }
    50% {
        -moz-transform: translateY(-20px) rotate(8deg);
    }
}
@-o-keyframes balloon1 {
    0%,
    100% {
        -o-transform: translateY(0) rotate(-6deg);
    }
    50% {
        -o-transform: translateY(-20px) rotate(8deg);
    }
}
@keyframes balloon1 {
    0%,
    100% {
        transform: translateY(0) rotate(-6deg);
    }
    50% {
        transform: translateY(-20px) rotate(8deg);
    }
}
/* BAllOON 2 5*/
@-webkit-keyframes balloon2 {
    0%,
    100% {
        -webkit-transform: translateY(0) rotate(6eg);
    }
    50% {
        -webkit-transform: translateY(-30px) rotate(-8deg);
    }
}
@-moz-keyframes balloon2 {
    0%,
    100% {
        -moz-transform: translateY(0) rotate(6deg);
    }
    50% {
        -moz-transform: translateY(-30px) rotate(-8deg);
    }
}
@-o-keyframes balloon2 {
    0%,
    100% {
        -o-transform: translateY(0) rotate(6deg);
    }
    50% {
        -o-transform: translateY(-30px) rotate(-8deg);
    }
}
@keyframes balloon2 {
    0%,
    100% {
        transform: translateY(0) rotate(6deg);
    }
    50% {
        transform: translateY(-30px) rotate(-8deg);
    }
}
/* BAllOON 0*/
@-webkit-keyframes balloon3 {
    0%,
    100% {
        -webkit-transform: translate(0, -10px) rotate(6eg);
    }
    50% {
        -webkit-transform: translate(-20px, 30px) rotate(-8deg);
    }
}
@-moz-keyframes balloon3 {
    0%,
    100% {
        -moz-transform: translate(0, -10px) rotate(6eg);
    }
    50% {
        -moz-transform: translate(-20px, 30px) rotate(-8deg);
    }
}
@-o-keyframes balloon3 {
    0%,
    100% {
        -o-transform: translate(0, -10px) rotate(6eg);
    }
    50% {
        -o-transform: translate(-20px, 30px) rotate(-8deg);
    }
}
@keyframes balloon3 {
    0%,
    100% {
        transform: translate(0, -10px) rotate(6eg);
    }
    50% {
        transform: translate(-20px, 30px) rotate(-8deg);
    }
}
/* BAllOON 3*/
@-webkit-keyframes balloon4 {
    0%,
    100% {
        -webkit-transform: translate(10px, -10px) rotate(-8eg);
    }
    50% {
        -webkit-transform: translate(-15px, 20px) rotate(10deg);
    }
}
@-moz-keyframes balloon4 {
    0%,
    100% {
        -moz-transform: translate(10px, -10px) rotate(-8eg);
    }
    50% {
        -moz-transform: translate(-15px, 10px) rotate(10deg);
    }
}
@-o-keyframes balloon4 {
    0%,
    100% {
        -o-transform: translate(10px, -10px) rotate(-8eg);
    }
    50% {
        -o-transform: translate(-15px, 10px) rotate(10deg);
    }
}
@keyframes balloon4 {
    0%,
    100% {
        transform: translate(10px, -10px) rotate(-8eg);
    }
    50% {
        transform: translate(-15px, 10px) rotate(10deg);
    }
}
h1 {
    position: relative;
    top: 200px;
    text-align: center;
    color: white;
    font-size: 3.5em;
}
.swal-overlay {
    background-color: rgba(218, 57, 177, 0.45);
}

.swal-text {
    font-size: 20px;
    font-weight: 200;
    word-spacing: 5px;
}

/* Hiệu ứng pháo hoa*/
.pyro > .before, .pyro > .after {
    position: absolute;
    width: 7px;
    height: 7px;
    pointer-events: none;
    z-index: 99999999;
    border-radius: 50%;
    box-shadow: -120px -218.66667px blue, 248px -16.66667px #00ff84, 190px 16.33333px #002bff, -113px -308.66667px #ff009d, -109px -287.66667px #ffb300, -50px -313.66667px #ff006e, 226px -31.66667px #ff4000, 180px -351.66667px #ff00d0, -12px -338.66667px #00f6ff, 220px -388.66667px #99ff00, -69px -27.66667px #ff0400, -111px -339.66667px #6200ff, 155px -237.66667px #00ddff, -152px -380.66667px #00ffd0, -50px -37.66667px #00ffdd, -95px -175.66667px #a6ff00, -88px 10.33333px #0d00ff, 112px -309.66667px #005eff, 69px -415.66667px #ff00a6, 168px -100.66667px #ff004c, -244px 24.33333px #ff6600, 97px -325.66667px #ff0066, -211px -182.66667px #00ffa2, 236px -126.66667px #b700ff, 140px -196.66667px #9000ff, 125px -175.66667px #00bbff, 118px -381.66667px #ff002f, 144px -111.66667px #ffae00, 36px -78.66667px #f600ff, -63px -196.66667px #c800ff, -218px -227.66667px #d4ff00, -134px -377.66667px #ea00ff, -36px -412.66667px #ff00d4, 209px -106.66667px #00fff2, 91px -278.66667px #000dff, -22px -191.66667px #9dff00, 139px -392.66667px #a6ff00, 56px -2.66667px #0099ff, -156px -276.66667px #ea00ff, -163px -233.66667px #00fffb, -238px -346.66667px #00ff73, 62px -363.66667px #0088ff, 244px -170.66667px #0062ff, 224px -142.66667px #b300ff, 141px -208.66667px #9000ff, 211px -285.66667px #ff6600, 181px -128.66667px #1e00ff, 90px -123.66667px #c800ff, 189px 70.33333px #00ffc8, -18px -383.66667px #00ff33, 100px -6.66667px #ff008c;
    -moz-animation: 1s bang ease-out infinite backwards, 1s gravity ease-in infinite backwards, 5s position linear infinite backwards;
    -webkit-animation: 1s bang ease-out infinite backwards, 1s gravity ease-in infinite backwards, 5s position linear infinite backwards;
    -o-animation: 1s bang ease-out infinite backwards, 1s gravity ease-in infinite backwards, 5s position linear infinite backwards;
    -ms-animation: 1s bang ease-out infinite backwards, 1s gravity ease-in infinite backwards, 5s position linear infinite backwards;
    animation: 1s bang ease-out infinite backwards, 1s gravity ease-in infinite backwards, 5s position linear infinite backwards; }
  
  .pyro > .after {
    -moz-animation-delay: 1.25s, 1.25s, 1.25s;
    -webkit-animation-delay: 1.25s, 1.25s, 1.25s;
    -o-animation-delay: 1.25s, 1.25s, 1.25s;
    -ms-animation-delay: 1.25s, 1.25s, 1.25s;
    animation-delay: 1.25s, 1.25s, 1.25s;
    -moz-animation-duration: 1.25s, 1.25s, 6.25s;
    -webkit-animation-duration: 1.25s, 1.25s, 6.25s;
    -o-animation-duration: 1.25s, 1.25s, 6.25s;
    -ms-animation-duration: 1.25s, 1.25s, 6.25s;
    animation-duration: 1.25s, 1.25s, 6.25s; }
  
  @-webkit-keyframes bang {
    from {
      box-shadow: 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white; } }
  @-moz-keyframes bang {
    from {
      box-shadow: 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white; } }
  @-o-keyframes bang {
    from {
      box-shadow: 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white; } }
  @-ms-keyframes bang {
    from {
      box-shadow: 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white; } }
  @keyframes bang {
    from {
      box-shadow: 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white; } }
  @-webkit-keyframes gravity {
    to {
      transform: translateY(200px);
      -moz-transform: translateY(200px);
      -webkit-transform: translateY(200px);
      -o-transform: translateY(200px);
      -ms-transform: translateY(200px);
      opacity: 0; } }
  @-moz-keyframes gravity {
    to {
      transform: translateY(200px);
      -moz-transform: translateY(200px);
      -webkit-transform: translateY(200px);
      -o-transform: translateY(200px);
      -ms-transform: translateY(200px);
      opacity: 0; } }
  @-o-keyframes gravity {
    to {
      transform: translateY(200px);
      -moz-transform: translateY(200px);
      -webkit-transform: translateY(200px);
      -o-transform: translateY(200px);
      -ms-transform: translateY(200px);
      opacity: 0; } }
  @-ms-keyframes gravity {
    to {
      transform: translateY(200px);
      -moz-transform: translateY(200px);
      -webkit-transform: translateY(200px);
      -o-transform: translateY(200px);
      -ms-transform: translateY(200px);
      opacity: 0; } }
  @keyframes gravity {
    to {
      transform: translateY(200px);
      -moz-transform: translateY(200px);
      -webkit-transform: translateY(200px);
      -o-transform: translateY(200px);
      -ms-transform: translateY(200px);
      opacity: 0; } }
  @-webkit-keyframes position {
    0%, 19.9% {
      margin-top: 10%;
      margin-left: 40%; }
  
    20%, 39.9% {
      margin-top: 40%;
      margin-left: 30%; }
  
    40%, 59.9% {
      margin-top: 20%;
      margin-left: 70%; }
  
    60%, 79.9% {
      margin-top: 30%;
      margin-left: 20%; }
  
    80%, 99.9% {
      margin-top: 30%;
      margin-left: 80%; } }
  @-moz-keyframes position {
    0%, 19.9% {
      margin-top: 10%;
      margin-left: 40%; }
  
    20%, 39.9% {
      margin-top: 40%;
      margin-left: 30%; }
  
    40%, 59.9% {
      margin-top: 20%;
      margin-left: 70%; }
  
    60%, 79.9% {
      margin-top: 30%;
      margin-left: 20%; }
  
    80%, 99.9% {
      margin-top: 30%;
      margin-left: 80%; } }
  @-o-keyframes position {
    0%, 19.9% {
      margin-top: 10%;
      margin-left: 40%; }
  
    20%, 39.9% {
      margin-top: 40%;
      margin-left: 30%; }
  
    40%, 59.9% {
      margin-top: 20%;
      margin-left: 70%; }
  
    60%, 79.9% {
      margin-top: 30%;
      margin-left: 20%; }
  
    80%, 99.9% {
      margin-top: 30%;
      margin-left: 80%; } }
  @-ms-keyframes position {
    0%, 19.9% {
      margin-top: 10%;
      margin-left: 40%; }
  
    20%, 39.9% {
      margin-top: 40%;
      margin-left: 30%; }
  
    40%, 59.9% {
      margin-top: 20%;
      margin-left: 70%; }
  
    60%, 79.9% {
      margin-top: 30%;
      margin-left: 20%; }
  
    80%, 99.9% {
      margin-top: 30%;
      margin-left: 80%; } }
  @keyframes position {
    0%, 19.9% {
      margin-top: 10%;
      margin-left: 40%; }
  
    20%, 39.9% {
      margin-top: 40%;
      margin-left: 30%; }
  
    40%, 59.9% {
      margin-top: 20%;
      margin-left: 70%; }
  
    60%, 79.9% {
      margin-top: 30%;
      margin-left: 20%; }
  
    80%, 99.9% {
      margin-top: 30%;
      margin-left: 80%; } }
      <!DOCTYPE html>
<html lang="vi" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="./Intro/intro.css">
    <script src="./Intro/intro.js"></script>
    <title>Happy Birthday</title>
    <link rel="shortcut icon" type="image/png" href="./MyBirthday/birthdayCake.png"/>
  </head>
  <body>
    <div class="content">
        <div id="container" class="container">
        <div class="counter">
          <span id="digit" class="digit">4</span>
        </div>
      </div>
    </div>
  </body>
</html>
