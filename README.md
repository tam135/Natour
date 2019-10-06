.LandingPage__app{
    background: linear-gradient(to bottom right,#ffffff 0,#d6dee9);
    background-size: cover;
    height: 200vh;
    font-family: DejaVu Sans;
}
.LandingPage__container {
    text-align: center;
    margin: auto auto;
    height: 150vh;
    padding: 1%;
    padding-top: 35%;
}

h1 {
    font-size: 45px;
}

h2 {
    font-size: 30px;
    font-weight: 500
}

h3 {
    font-size: 30px;
}

p {
    font-size: 20px;
    font-weight: 400
}


.LandingPage__Tagline {
    width: 90%;
    margin: auto auto;
}

.LandingPage__description1 {
    margin: auto auto;
    width: 80%;
    padding-top: 50vh;
}


.LandingPage__description2{
    margin: auto auto;
    width: 80%;
    margin-top: 75px;
}



.demo-button{
    background: linear-gradient(to bottom right,#64fa84 0,#00c96b);
    width: 200px;
    font-size: 25px;
    margin-top: 45px;
}

.demo-button:hover {
    background: #26F1CB;
    transform: scale(1.1);
}
.screenshot1 {
    /* height: 150px; */
   /*  width: 90%; */
}

.screenshot2 {
    height: 150px;
    width: 250px;
}

footer {
    position: fixed;
    left: 0;
    bottom: 0;
    height: 30px;
    width: 100%;
    background-color: #1081C7;
    color: white;
    text-align: center;
    padding: .5%;
}

@media only screen and (min-width: 768px) {

    .LandingPage__container {
        width: 70%;
        text-align: center;
        margin: auto auto;
        padding: 5%;
        padding-top: 10%;
    }

    .LandingPage__title {
        font-size: 65px;
    }

    .LandingPage__description1{
        margin: auto auto;
       
        width: 80%
    }



    .demo-button {
        margin-top: 50px;
        width: 200px;
    }
    .button-container {
        width: 80%;
        height: 100px;
        margin: 25px auto;
    }
    login-button, reg-button {
        display: inline-block;
        width: 200px;
        margin: 50px 25px;
        border-radius: 5px;
        padding: 20px;
        font-size: 25px;
    } 
    .demo-button{
        width: 200px;
        font-size: 25px;
    }
}