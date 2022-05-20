    body{
        height: 1550px;
    }
    .parent{
        width: 350px;
        font-family: 'League Spartan', sans-serif;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50% , -50%);
        background-color: white;
        height: 1350px;
        margin: 20px auto;
    }
    .parent > div:nth-of-type(1){
        height: 232px;
        width: 350px;
        background-image: url(../images/bg-pattern-top-mobile.svg);
        position: absolute;
    }
    .parent > div:nth-of-type(2){
        width: 1085px;
        height: 670px;
        background-image: url(../images/bg-pattern-bottom-desktop.svg);
        position: absolute;
        right: -198px;
        top: 32px;
        opacity: 0;
    }
    .parent h1{
        font-weight: 700;
        font-size: 40px;
        text-align: center;
        margin: 80px 0px 30px;
        color: hsl(300, 43%, 22%);
    }
    .parent > p:nth-of-type(1){
        text-align: center;
        width: 300px;
        line-height: 1.2;
        margin: 0px auto;
        font-weight: 500;
        color: hsl(303, 10%, 53%);
    }
    .box{
        width: 320px;
        height: 70px;
        text-align: center;
        padding: 15px;
        background-color: #f7f2f8;
        margin: 15px auto;
        border-radius: 10px;
    }
    .star{
        font-size: 25px;
        margin-bottom: 5px;
    }
    .box p{
        font-weight: 700;
        color: hsl(300, 43%, 22%);
    }
    .box-user{
        width: 320px;
        height: 220px;
        background-color: hsl(300, 43%, 22%);
        margin: 30px auto;
        padding: 25px;
        border-radius: 10px;
        color: white;
    }
    .box-user .top{
        height: 70px;
        display: flex;
    }
    .box-user .top img{
        width: 50px;
        height: 50px;
        border-radius: 50%;
        margin-right: 20px;
    }
    .box-user .top p{
        width: 100px;
        font-weight: 700;
    }
    .box-user .top span{
        margin-top: 10px;
        color: #c06097;
        font-weight: 400;
    }
    .box-user p{
        width: 258px;
        line-height: 1.3;
    }