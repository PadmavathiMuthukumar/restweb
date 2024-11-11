# Ex.07 Restaurant Website
## Date: 11-11-2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
## home.html
```
<html>
    <head>
        <title>Snegha Hotels</title>
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

        <style>
            
            .container{
                width: 1500px;
                height: 100%;
                position: absolute;
                
            }
            body{
                overflow-x: hidden;
                margin: 0;
            }
            .box{
                width: 1500px;
                height: 110px;
                background-image: url('https://img.freepik.com/free-photo/grunge-black-concrete-textured-background_53876-124541.jpg');
                
                position: relative;
                
                
                
            }
            h1{
                top: 10%;
                left: 2%;
                color: rgb(248, 243, 243);
                font-family: Castellar;
                position: relative;
                font-size: 50px;
                text-shadow:  0 0 5px #ffffff,   /* Subtle glow close to the text */
                   0 0 15px #ffffff;
            }
            .word{
                position: absolute;
                bottom: 10px;
                right: 20px;

            }
            .word a{
                text-decoration: none;
                color:crimson;
                margin-left: 15px;
                
            }
            .word button{
                border: none;
                background: none;
                padding: 5px 5px;
                cursor: pointer
            }
            .word button:hover{
                background-color: white;
                border-radius: 5px ;    
            }
            .class{
                
                height: 600px;
                width:1500px;
                
                top: 15%;
                background-image: url('https://media.istockphoto.com/id/1392502862/photo/smoke-background.jpg?s=612x612&w=0&k=20&c=JDPZDRlGJDvMVtnQ7Fq12X0qTbo757njDqiqbG5n12U=');
               
                background-size: cover;


            }
            .class h2{
                position: relative;
                color: white;
                top: 5%;
                left: 15%;
                font-family: Algerian;

            }
            .class img{
                
                position: absolute;
                top: 25%;
                left: 95%;
            }
            .class p{
                color: aliceblue;
                position:absolute;
                top: 30%;
                left: 5%;
                right: 20%;
            }
            .time {
                width: 250px;
                height: 250px;
                border-radius: 5px;
                background: transparent;
                position: absolute;
                top: 50%;
                left: 50%;


            }
            .time p{
                left: 50;
                color:white;
                font-size: 30px;
                font-family: Blackadder ITC;
            }
           footer{
            text-align: center;
            color:rgb(247, 240, 240);
            background-color: black;
            width:1500px;
           }
          
            
            
            
            
            
            
        

        </style>

    </head>
    <body>
        <div class="container">
            <div class="box">
                <h1>Burger King Restaurant</h1>
                <nav class="word">
                    <button><a href="home.html">Home</a></button>
                    <button><a href="menu.html">Menu</a></button>
                    <button><a href="admin.html">Administrator</a></button>
                    <button><a href="contact.html">Contact us</a></button>
                </nav>

            </div>
            <div class="class">
                <h2>About Us</h2>
                <img src="https://png.pngtree.com/png-clipart/20221001/ourmid/pngtree-fast-food-big-ham-burger-png-image_6244235.png">
                <p>
                   <b> Welcome to Burger King,</b> where flavor meets excellence! Our restaurant is designed to offer a delightful dining experience with a menu that caters to every taste. From mouthwatering burgers to refreshing beverages, we take pride in serving you the best. At Burger King, we focus on quality, comfort, and exceptional service, ensuring every visit is a memorable one. Join us for a meal and let us treat you to a feast you’ll love!
                </p>
                
                
            </div>
            
            <div class="time">
                <p>Timings
                    <br>
                    10:00 am - 3:00 pm
                </p>
                <img src="https://static.vecteezy.com/system/resources/previews/016/326/810/non_2x/clock-icon-transparent-background-free-png.png" width="200px" height="150px" style="align-content: center;">
                
               

            </div>
            <footer>
                <p>&copy; 2024 Burger King. All rights reserved.</p>
                </footer>
        </div>
        
    </body>
</html>
```
## menu.html
```
<html>
    <head>
        <title>snegha hotels</title>
    </head>
    <style>
        .box{
                width: 100%;
                height: 110px;
                background-image: url('https://img.freepik.com/free-photo/grunge-black-concrete-textured-background_53876-124541.jpg');
                
                position: relative;
                
                
                
            }
            h1{
                top: 10%;
                left: 2%;
                color:rgba(255, 255, 255, 0.915);
                font-family: Castellar;
                position: relative;
                font-size: 50px;
                text-shadow: 0 0 5px whitesmoke;
             }
             body{
                overflow-x: hidden;
                margin: 0;
             }

            .word{
                position: absolute;
                bottom: 10px;
                right: 20px;

            }
            .word a{
                text-decoration: none;
                color:crimson;
                margin-left: 15px;
                
            }
            .word button{
                border: none;
                background: none;
                padding: 5px 5px;
                cursor: pointer
            }
            .word button:hover{
                background-color: white;
                border-radius: 5px ;   
            }
            .sec{
                width:100%;
                height: 100%;
            }
            .sec h2{
                font-family: Algerian;
                color: rgb(235, 187, 13);
                position: absolute;
                top: 10%;
                
                left: 45%;
                font-size: 50px;
                
            }
            .dish{
                position: absolute;
                left: 40%;
                top: 22%;
            }
            .dish h3{
                font-size: 30px;
                font-family: Colonna MT;
                color: rgba(12, 240, 244, 0.803);
                margin-bottom: 1;
            }
            .dish p{
                font-size: 20px;
                color: aliceblue;
                margin-top: 1px;
                margin-bottom:1px;

            }
            footer{
            position:fixed;
            text-align: center;
            color:rgb(247, 240, 240);
            background-color: black;
            width:100%;
            bottom: 0%;
            
           }
           body{
                overflow-y: hidden;
                margin: 0;
            }
            .img1{
                position: absolute;
                left: 5%;
                top: 30%;
                width: 300px;
                height:300px;
                background: transparent;

            }
            .img2{
                position: absolute;
                right: 5%;
                top: 30%;
                width: 300px;
                height:300px;
                background: transparent;

            }

    </style>
    <body>
       
        <div class="box">
            <h1>Burger King Restaurant</h1>
            <nav class="word">
                <button><a href="home.html">Home</a></button>
                <button><a href="menu.html">Menu</a></button>
                <button><a href="admin.html">Administrator</a></button>
                <button><a href="contact.html">Contact us</a></button>
            </nav>

        </div>
        <div class="sec">
            <img src="https://images.pond5.com/light-smoke-ambiance-effect-isolated-footage-034508565_iconl.jpeg" width="100%" height="100%">
            <h2>Menu</h2>

        </div>
        <div class="dish">
            <h3>Starters</h3>
            
            <p>Spring Roll      -     Rs.59</p> 
            <p>Garlic bread     -     Rs.89</p>
            <p>Veg Sandwich    -     Rs.99</p>
            <h3>Main Course</h3>
            <p>Veg Burger    -  Rs.189</p>
            <p>Chicken Burger - Rs.289</p>
            <p>Tandoori Burger - Rs.309</p>
            <p>Veg Pizza - Rs.99</p>
            <p>Chicken Pizza - Rs.159</p>
            <h3>Desserts</h3>
            <p>Choco Lava Cake - Rs.99</p>
            <p>Cheese Cake - Rs.199</p>
            <p>Brownie - Rs.159</p>
        </div>
        <img src="https://png.pngtree.com/png-vector/20231018/ourmid/pngtree-fast-foods-item-png-image_10303953.png" class="img1">
        <img src="https://static.vecteezy.com/system/resources/thumbnails/037/079/786/small_2x/ai-generated-fast-food-fresh-delicious-burger-high-quality-isolated-transparent-background-png.png" class="img2">

        <footer>
            &copy; 2024 Burger King(padma). All rights reserved.
        </footer>

    </body>
</html>
```
## admin.html
```
<html>
    <head>
        <title>
            snegha hotels
        </title>
        <style>
             .box{
                width: 100%;
                height: 110px;
                background-image: url('https://img.freepik.com/free-photo/grunge-black-concrete-textured-background_53876-124541.jpg');
                
                position: relative;
                
                
                
            }
            h1{
                top: 10%;
                left: 2%;
                color:rgba(255, 255, 255, 0.915);
                font-family: Castellar;
                position: relative;
                font-size: 50px;
                text-shadow: 0 0 5px whitesmoke;
             }
             body{
                overflow-x: hidden;
                margin: 0;
             }

            .word{
                position: absolute;
                bottom: 10px;
                right: 20px;

            }
            .word a{
                text-decoration: none;
                color:crimson;
                margin-left: 15px;
                
            }
            .word button{
                border: none;
                background: none;
                padding: 5px 5px;
                cursor: pointer
            }
            .word button:hover{
                background-color: white;
                border-radius: 5px ;   
            }
            .pic{
                width:200px;
                height:200px;
                top: 20%;
                left:5%;
                position:absolute;
                border-radius: 5px;
            }
            h2{
                position:absolute;
                top: 47%;
                left: 5%;
                color: white;
            }
            .pic1{
                width: 200px;
                height: 200px;
                top:20%;
                left: 20%;
                position:absolute;
                border-radius: 5px;
            }
            h3{
                top:46%;
                position:absolute;
                left: 20%;
                color:white;
                font-size: 25px;
            }
            .pic2{
                width: 200px;
                height: 200px;
                top:20%;
                left: 36%;
                position:absolute;
                border-radius: 5px;

            }
            h4{
                top:46%;
                position:absolute;
                left: 36%;
                color:white;
                font-size: 25px;
            }
            .pic3{
                width: 200px;
                height: 200px;
                top:20%;
                left: 52%;
                position:absolute;
                border-radius: 5px;

            }
            h5{
                top:46%;
                position:absolute;
                left: 52%;
                color:white;
                font-size: 25px;
            }
            .pic4{
                width: 200px;
                height: 200px;
                top:20%;
                left: 68%;
                position:absolute;
                border-radius: 5px;

            }
            h6{
                top:47%;
                position:absolute;
                left: 68%;
                color:white;
                font-size: 25px;
            }
            .pic5{
                width: 200px;
                height: 200px;
                top:20%;
                left: 85%;
                position:absolute;
                border-radius: 5px;

            }
            p{
                top:47%;
                position:absolute;
                left: 85%;
                color:white;
                font-size: 25px;


            }
            footer{
            position:absolute;
            text-align: center;
            color:rgb(247, 240, 240);
            background-color: black;
            width:100%;
            height:60px;
           }
           footer{
                    position:fixed;
                    text-align: center;
                    color:rgb(247, 240, 240);
                    background-color: black;
                    width:100%;
                    height: 20px;
                    bottom:0%;
                   }
            body{
                overflow-y: hidden;
                margin: 0;
            }

        </style>
        <body>
            <div class="box">
                <h1>Burger King Restaurant</h1>
                <nav class="word">
                    <button><a href="home.html">Home</a></button>
                    <button><a href="menu.html">Menu</a></button>
                    <button><a href="admin.html">Administrator</a></button>
                    <button><a href="contact.html">Contact us</a></button>
                </nav>

    
            </div>
            <div>
                <img src="https://i.pinimg.com/736x/d7/98/57/d798571efb75d26b0ece1c936bcf6368.jpg" width="100%" height="100%">
                <img src="C:\Users\padma\Downloads\IMG-20230906-WA0050.jpg" class="pic">
                <h2>M Padmavathi<br>
                ~ General Manager</h2>
                <img src="https://yt3.googleusercontent.com/ytc/AIdro_lE3vUCghFX5WQbJGcsyuPAg9n5fIEp0LCUCwa3mAYrSow=s900-c-k-c0x00ffffff-no-rj" class="pic1">
                <h3>Dora<br>
                ~ Receptionist</h3>
                <img src="https://i.pinimg.com/736x/37/14/c4/3714c4f90135d9e3fab5fb81c73efef8.jpg" class="pic2">
                <h4>Hattori<br>
                ~ Housekeeping
                <br> Attendant</h4>
                <img src="https://img.etimg.com/thumb/width-1200,height-900,imgsize-212710,resizemode-75,msid-75201793/magazines/panache/playtime-on-tv-pogo-prasar-bharati-join-hands-to-air-chhota-bheem-on-dd-national.jpg" class="pic3">
                <h5>Chotta Bheem
                    <br>~ Chef

                </h5>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR1qVy1gV8TH1gyMRZGe4-WSf-ELoTMov-AsIr46Ug5q6sZp9yVjdkHs_b2Pksu-BXvKwk&usqp=CAU" class="pic4">
                <h6>Kaliya<br>~ Security<br>Manager</h6>
                <img src="https://i.pinimg.com/736x/8a/ca/0f/8aca0f69d3ff616a84c24af49735e6d7.jpg" class="pic5">
                <p>Shin chan<br>~ Salesman</p>

                <footer>
                    <p>&copy; 2024 Burger King(padma). All rights reserved.</p>
                    </footer>
                
                
            </div>
            <footer>
                &copy; 2024 Burger King(padma). All rights reserved.
                </footer>
        </body>
    </head>
</html>
```
## contact.html
```
<html>
    <head>
        <title>Snegha hotels</title>
        <style>
            .box{
                width: 100%;
                height: 110px;
                background-image: url('https://img.freepik.com/free-photo/grunge-black-concrete-textured-background_53876-124541.jpg');
                
                position: relative;
                
                
                
            }
            h1{
                top: 10%;
                left: 2%;
                color:rgba(255, 255, 255, 0.915);
                font-family: Castellar;
                position: relative;
                font-size: 50px;
                text-shadow: 0 0 5px whitesmoke;
             }
             body{
                overflow-x: hidden;
                margin: 0;
             }

            .word{
                position: absolute;
                bottom: 10px;
                right: 20px;

            }
            .word a{
                text-decoration: none;
                color:crimson;
                margin-left: 15px;
                
            }
            .word button{
                border: none;
                background: none;
                padding: 5px 5px;
                cursor: pointer
            }
            .word button:hover{
                background-color: white;
                border-radius: 5px ;   
            }
            h2{
                color: aliceblue;
                font-family: Franklin Gothic Heavy;
                position: absolute;
                top: 25%;
                left: 25%;
                font-size: 50px;
            }
            p{
                color: crimson;
                font-family: Colonna MT;
                top: 35%;
                left: 25%;
                position: absolute;
                font-size: 40px;
            }
            .pic{
                width: 400px;
                height: 400px;
                background: transparent;
                position: absolute;
                right: 10%;
            }
            .pic2{
                width: 300px;
                height: 300px;
                position: absolute;
                top: 22%;
                left: 0%;
            }
            footer{
            position:fixed;
            text-align: center;
            color:rgb(247, 240, 240);
            background-color: black;
            width:100%;
            height:20px;
            bottom:0%;
           }
           body{
                overflow-y: hidden;
                margin: 0;
            }


        </style>
        <body>
            <div class="box">
                <h1>Burger King Restaurant</h1>
                <nav class="word">
                    <button><a href="home.html">Home</a></button>
                    <button><a href="menu.html">Menu</a></button>
                    <button><a href="admin.html">Administrator</a></button>
                    <button><a href="contact.html">Contact us</a></button>
                </nav>
    
            </div>
            <div>
                <img src="https://st3.depositphotos.com/1105977/18780/v/600/depositphotos_187803882-stock-video-slow-motion-realistic-smoke-effect.jpg" width="100%" height="100%">
                <h2>For Contact</h2>
                <p>Phone No.: 8348039990<br>
                Email: burgerking@gmail.com</p>
                <img src="https://static.vecteezy.com/system/resources/previews/035/982/234/non_2x/ai-generated-delicious-burger-isolated-on-transparent-background-free-png.png" class="pic">
                
                <img src="https://png.pngtree.com/png-vector/20230321/ourmid/pngtree-modern-kitchen-food-box-italian-pizza-png-image_6651521.png" class="pic2">
                <footer>
                    &copy; 2024 Burger King(padma). All rights reserved.
                </footer>
            </div>

        </body>
    </head>
</html>
```
## OUTPUT:
## home.html:
![image](https://github.com/user-attachments/assets/873991b9-e3ab-4151-905f-e4fae28fb27f)

## menu.html
![image](https://github.com/user-attachments/assets/6f8724a9-caec-44e4-bd8b-79cb04ac2f45)

## admin.html
![image](https://github.com/user-attachments/assets/3da6ca77-f1df-42ce-9ed0-08db32a39c26)

## contact.html:
![Screenshot 2024-11-11 113431](https://github.com/user-attachments/assets/d9fdee4b-811a-4018-891f-ca4ef98288c5)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
