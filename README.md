# SRM-Hackathon
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content = "This is description">
    <meta name="keywords" content = "geetanj html,html tutorials">
    <meta name="robots" content = "INDEX,FOLLOW">
    <title>Farmer Portal</title>
</head>
<style>
    *{
        border: 2px solid red;
        padding: 7px;
    }
    /* css reset */
    body {
        color: white;
        margin: 0px;
        padding: 0px;
        /* background: url('pics/jpg.jpg'); */
        /* font-family: 'Baloo Bhai 2', cursive; */
        /* height: 45575px */
    }

    .left {
        position: absolute;
        left: 34px;
        top: 20px;
        display: inline-block;
        border: 2px solid red;
    }
    .left img{
        width: 126px;
        filter: invert(100%);

    }
    .left div{
        text-align: center;
    }
    

    .mid {
        display: block;
        width: 33%;
        margin: 20px auto;
        border: 2px solid yellow;

    }

    .right {
        position: absolute;
        right: 34px;
        top: 20px;
        display: inline-block;
        border: 2px solid green;

    }
    .navbar{
        display:inline-block;
    }
    .navbar li{
        display: inline-block;
        font-size: 20px;
    }
    .navbar li a{
        color: white;
        text-decoration: none;
        padding: 14px 6px;
    }
    .navbar li a:hover,
    .navbar li a.active {
        text-decoration: underline;
        color:grey
    }
    .btn{
        margin: 0px 9px;
        background-color: black;
        color: white;
        padding: 4px 14px;
        border:2px solid grey;
        border-radius: 10px;
        font-size: 18px;
        cursor: pointer;
        /* font-family: 'Baloo Bhai 2', cursive; */
    }
    .btn:hover{
        background-color: gray;
    }
</style>
<body>
    <header class="header">
        <!-- left box for logo -->
        <div class="left">
            <button class="btn">Home</button>
            <button class="btn">Documents</button>


        </div>
        <!-- Mid box for navbar -->
        <div class="mid">
         
            <!-- I am mid . -->

        </div>
        <!-- right box for buttons -->
        <div class="right">
            <button class="btn">Call Us Now</button>
            <button class="btn">Email Us</button>
            <!-- I am right. -->
        </div>
    </header>

</body>


    
</body>
</html>
