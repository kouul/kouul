<style>
h1 {
    display: block;
    font-size: 3em;
    margin: 0.6em 0;
    font-weight: bold;
}

.glitch {
    margin: 0 auto;
    color: #fff;
    width: fit-content;
    text-align: center;
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
}

.glitch::before, .glitch::after {
    content: attr(data-text);
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    overflow: hidden;
    background: #000;
    /* background-image: url('/static/images/bg/banner.jpg'); */
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover; 
    opacity: 0.9;
    color: white;
    clip: rect(0, 900px, 0, 0);
}

.glitch::before {
    left: 7px;
    text-shadow: 2px 5px orangered;
    animation: glitch-effect 5s infinite linear alternate-reverse;
}

.glitch::after {
    left: 3px;
    text-shadow: -2px 2px lime;
    animation: glitch-effect 10s infinite linear alternate-reverse;
}

@-webkit-keyframes glitch-effect {
    0% {
        clip: rect(3px, 9999px, 84px, 0);
    }
    5% {
        clip: rect(82px, 9999px, 7px, 0);
    }
    10% {
        clip: rect(4px, 9999px, 50px, 0);
    }
    15% {
        clip: rect(63px, 9999px, 51px, 0);
    }
    20% {
        clip: rect(82px, 9999px, 39px, 0);
    }
    25% {
        clip: rect(4px, 9999px, 76px, 0);
    }
    30% {
        clip: rect(57px, 9999px, 94px, 0);
    }
    35% {
        clip: rect(55px, 9999px, 12px, 0);
    }
    40% {
        clip: rect(13px, 9999px, 4px, 0);
    }
    45% {
        clip: rect(75px, 9999px, 61px, 0);
    }
    50% {
        clip: rect(73px, 9999px, 20px, 0);
    }
    55% {
        clip: rect(74px, 9999px, 91px, 0);
    }
    60% {
        clip: rect(100px, 9999px, 73px, 0);
    }
    65% {
        clip: rect(76px, 9999px, 61px, 0);
    }
    70% {
        clip: rect(95px, 9999px, 86px, 0);
    }
    75% {
        clip: rect(59px, 9999px, 86px, 0);
    }
    80% {
        clip: rect(92px, 9999px, 80px, 0);
    }
    85% {
        clip: rect(30px, 9999px, 11px, 0);
    }
    90% {
        clip: rect(37px, 9999px, 27px, 0);
    }
    95% {
        clip: rect(54px, 9999px, 54px, 0);
    }
    100% {
        clip: rect(5px, 9999px, 74px, 0);
    }
}

@keyframes glitch-effect {
    0% {
        clip: rect(3px, 9999px, 84px, 0);
    }
    5% {
        clip: rect(82px, 9999px, 7px, 0);
    }
    10% {
        clip: rect(4px, 9999px, 50px, 0);
    }
    15% {
        clip: rect(63px, 9999px, 51px, 0);
    }
    20% {
        clip: rect(82px, 9999px, 39px, 0);
    }
    25% {
        clip: rect(4px, 9999px, 76px, 0);
    }
    30% {
        clip: rect(57px, 9999px, 94px, 0);
    }
    35% {
        clip: rect(55px, 9999px, 12px, 0);
    }
    40% {
        clip: rect(13px, 9999px, 4px, 0);
    }
    45% {
        clip: rect(75px, 9999px, 61px, 0);
    }
    50% {
        clip: rect(73px, 9999px, 20px, 0);
    }
    55% {
        clip: rect(74px, 9999px, 91px, 0);
    }
    60% {
        clip: rect(100px, 9999px, 73px, 0);
    }
    65% {
        clip: rect(76px, 9999px, 61px, 0);
    }
    70% {
        clip: rect(95px, 9999px, 86px, 0);
    }
    75% {
        clip: rect(59px, 9999px, 86px, 0);
    }
    80% {
        clip: rect(92px, 9999px, 80px, 0);
    }
    85% {
        clip: rect(30px, 9999px, 11px, 0);
    }
    90% {
        clip: rect(37px, 9999px, 27px, 0);
    }
    95% {
        clip: rect(54px, 9999px, 54px, 0);
    }
    100% {
        clip: rect(5px, 9999px, 29px, 0);
    }
}

</style>
<h5 style="padding: 0; margin: 0;" class="title-style">Yo! I'm </h5>
<h4 class="title-style glitch glitch-text name" style="font-size: calc(1vw + 4vh + 2vmin);" data-text="Akhil">Hans Maulloo</h4>