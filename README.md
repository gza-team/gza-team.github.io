<!DOCTYPE html>
<html>
<head>
    <title>Wiki Stick Man</title>
    <style>
        body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #000;
}

.stickman {
    position: relative;
    width: 150px;
    height: 200px;
}

.stickman div {
    position: absolute;
    background-color: #fff;
    opacity: 0.8;
}

.head {
    top: 0;
    left: 50%;
    transform: translateX(-50%);
    border-radius: 50%;
    width: 60px;
    height: 60px;
}

.body {
    top: 60px;
    left: 50%;
    transform: translateX(-50%);
    width: 6px;
    height: 100px;
}

.left-arm,
.right-arm {
    top: 75px;
    width: 50px;
    height: 6px;
}

.left-arm {
    left: -50px;
}

.right-arm {
    right: -50px;
}

.left-leg,
.right-leg {
    top: 160px;
    width: 6px;
    height: 70px;
}

.left-leg {
    left: 50%;
    transform: translateX(-50%);
}

.right-leg {
    right: 50%;
    transform: translateX(50%);
}
</style>
</head>
<body>
    <div class="stickman">
        <div class="head"></div>
        <div class="body"></div>
        <div class="left-arm"></div>
        <div class="right-arm"></div>
        <div class="left-leg"></div>
        <div class="right-leg"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>
