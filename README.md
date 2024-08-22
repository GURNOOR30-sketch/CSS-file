# CSS-file
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: montserrat;
}

body {
    background: #f7f6f2;
}

.container {
    background: #e7edee;
    max-width: 800px;
    margin: 60px auto;
    height: 1250px;
    padding: 20px;
    box-shadow: 0 2px 20px rgba(0, 0, 0, 0.3);
}

.header {
    text-align: center;
}

.header h1 {
    margin-bottom: 10px;
}

.header h3 {
    text-transform: uppercase;
    font-size: 15px;
    font-weight: 500;
}

.img area {
    width: 100px;
    height: 200px;
    border-radius: 50%;
    overflow: hidden;
    margin-right :90 px;
    border: 15px groove deepskyblue
}

.img-area img {
    width:30%
    height:30%
    margin:auto
}

.main {
    display: flex;
    justify-content: flex-end;
    height:100vh;
    align-items:flex-end;
    flex-wrap: wrap;
}

.left {
    flex: 1;
    padding: 30px;
}

.left p {
    flex: 1;
    padding: 30px;
}

.left p {
    line-height: 2;
}

.left ul li {
    line-height: 2
}

h2 {
    background: #00b6c4;
    padding: 15px;
    color: #fff;
    margin: 30px;
    font-size: 20px;
    border-radius: 0 50px 50px 0;
}
