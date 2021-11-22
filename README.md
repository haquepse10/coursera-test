# coursera-test
Coursera test Repository
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    transition: 0.5s;
    font-family: "Century Gothic", sans-serif;
}

.navlist {
    width: 100%;
    position: fixed;
    padding: 5px 10%;
    background-color: #110e2bbb;
}

.navlist ul {
    display: flex;
    list-style: none;
}

.navlist ul li:first-child {
    flex: 1;
    color: #ffffff;
}

.navlist ul li h4 {
    font-family: serif;
}

.navlist ul a {
    display: block;
    margin-left: 20px;
    font-family: "Century Gothic", sans-serif;
    font-size: 0.9rem;
    color: white;
    text-decoration: none;
}

.navlist ul a:hover {
    color: #ff8800;
}

.main-box {
    width: 100%;
    height: 80vh;
    background-image: linear-gradient(#(#000000bb, #000000bb), url(../images/background.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    color: #ffffff;
    text-align: center;
    padding-top: 30vh;
}

.main-box h1 {
    word-spacing: 8px;
    margin-bottom: 15px;
    font-family: serif;
}

.main-box p {
    font-family: "Century Gothic", sans-serif;
    font-size: 14px;
    letter-spacing: 1.4px;
    margin-bottom: 40px;
}

.main-box button {
    padding: 10px;
    border: none;
    outline: none;
    background: none;
    border: 1px solid #ff8800;
    color: #ffffff;
}

.main-box button:hover {
    background: #ff8800;
}

.container {
    width: 80%;
    margin: auto;
    margin-bottom: 30px;
}

.container h2 {
    color: #ff8800;
    text-align: center;
    margin: 30px;
    font-family: 'Arial Narrow Bold', sans-serif;
    letter-spacing: 5px;
}

.container h2::before,
.container h2::after {
    content: "-----";
    letter-spacing: -5px;
    font-weight: lighter;
    margin: 0 20px 0 10px;
}

.container .row {
    display: flex;
    justify-content: space-between;
}

.container .column {
    width: 32%;
    height: auto;
    position: relative;
    overflow: hidden;
}

.container .column img {
    width: 100%;
    height: auto;
}

.container .column a:last-child {
    position: absolute;
    display: block;
    width: 100%;
    height: 0;
    top: 99%;
    bottom: 0;
    left: 0;
    bottom: 0;
    background-color: #ff8800c0;
    text-align: center;
    padding-top: 14vw;
    font-size: 3vw;
    color: #ffffff;
    text-decoration: none;
}

.container .column:hover a:last-child {
    height: 100%;
    top: 0;
}
