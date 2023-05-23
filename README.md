### Hi there 👋
<style>
    @font-face {
        font-family: 'Coop';
        src: url('https://s3-us-west-2.amazonaws.com/s.cdpn.io/383755/cooper-black-webfont.woff') format('woff');
        font-weight: normal;
        font-style: normal;
    }

    body {
        background: #222;
        width: 100%;
        height: 100vh;
        overflow: hidden;
        font-family: "Coop";
    }

    .wrap {
        position: absolute;
        left: 50%;
        top: 50%;
        width: 300px;
        height: 300px;
        transform: translateX(-50%) translateY(-50%);
    }

    .wrap h1 {
        text-shadow: -1px -1px 0 #26A69A, -1px 0px 0 #26A69A, -1px 1px 0 #26A69A, 0px -1px 0 #26A69A, 0px 0px 0 #26A69A, 0px 1px 0 #26A69A, 1px -1px 0 #26A69A, 1px 0px 0 #26A69A, 1px 1px 0 #26A69A;
        color: #222;
        position: absolute;
        font-size: 100px;
        text-align: center;
        line-height: 0.75;
    }

    .wrap h1:nth-of-type(1) {
        margin-top: 5px;
        text-shadow: -1px -1px 0 #080000, -1px 0px 0 #080000, -1px 1px 0 #080000, 0px -1px 0 #080000, 0px 0px 0 #080000, 0px 1px 0 #080000, 1px -1px 0 #080000, 1px 0px 0 #080000, 1px 1px 0 #080000;
        animation: bounce 1s ease-in-out infinite;
        animation-delay: -0.05s;
        will-change: transform;
    }

    .wrap h1:nth-of-type(2) {
        margin-top: 10px;
        text-shadow: -1px -1px 0 #161300, -1px 0px 0 #161300, -1px 1px 0 #161300, 0px -1px 0 #161300, 0px 0px 0 #161300, 0px 1px 0 #161300, 1px -1px 0 #161300, 1px 0px 0 #161300, 1px 1px 0 #161300;
        animation: bounce 1s ease-in-out infinite;
        animation-delay: -0.1s;
        will-change: transform;
    }

    .wrap h1:nth-of-type(3) {
        margin-top: 15px;
        text-shadow: -1px -1px 0 #242200, -1px 0px 0 #242200, -1px 1px 0 #242200, 0px -1px 0 #242200, 0px 0px 0 #242200, 0px 1px 0 #242200, 1px -1px 0 #242200, 1px 0px 0 #242200, 1px 1px 0 #242200;
        animation: bounce 1s ease-in-out infinite;
        animation-delay: -0.15s;
        will-change: transform;
    }

    /* ... 중간 생략 ... */

    .wrap h1:nth-of-type(20) {
        margin-top: 100px;
        text-shadow: -1px -1px 0 #FFFF00, -1px 0px 0 #FFFF00, -1px 1px 0 #FFFF00, 0px -1px 0 #FFFF00, 0px 0px 0 #FFFF00, 0px 1px 0 #FFFF00, 1px -1px 0 #FFFF00, 1px 0px 0 #FFFF00, 1px 1px 0 #FFFF00;
        animation: bounce 1s ease-in-out infinite;
        animation-delay: -1s;
        will-change: transform;
    }

    .wrap h1 span {
        display: inline-block;
        animation: rotate 1s ease-in-out infinite alternate;
        will-change: transform;
    }

    .wrap h1 span:nth-of-type(1) {
        animation-delay: -0.2s;
    }

    .wrap h1 span:nth-of-type(2) {
        animation-delay: -0.4s;
    }

    .wrap h1 span:nth-of-type(3) {
        animation-delay: -0.6s;
    }

    /* ... 중간 생략 ... */

    .wrap h1 span:nth-of-type(20) {
        animation-delay: -4s;
    }

    @keyframes bounce {
        0% {
            transform: translateY(0px) translateX(-10px) translateZ(0);
        }
        50% {
            transform: translateY(-10px) translateX(10px) translateZ(0);
        }
        100% {
            transform: translateY(0px) translateX(-10px) translateZ(0);
        }
    }

    @keyframes rotate {
        0% {
            transform: rotate(-25deg) translateZ(0);
        }
        100% {
            transform: rotate(25deg) translateZ(0);
        }
    }
</style>
<script>
    $("h1").html(function(index, html) {
        return html.replace(/\S/g, '<span>$&</span>');
    });
</script>
<div class="wrap">
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
    <h1>WEBSTORYBOY</h1>
</div>
