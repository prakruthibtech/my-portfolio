<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link
    href="https://cdn.jsdelivr.net/npm/remixicon@4.0.0/fonts/remixicon.css"
    rel="stylesheet"
/>
    
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Lora:ital,wght@1,500&display=swap');

* {
    margin:0;
    padding:0;
    box-sizing: border-box;
}

html,body{
    width: 100%;
    height:100%
}

body {
    margin: 0;
    padding: 0;
    overflow: hidden; /* Prevent scrolling on the body */
}

#main {
    display: flex;
    width: 85%;
    height: 80%;
    margin: 5%;
    backdrop-filter: blur(50px); /* Adjust the blur radius as needed */
    background-color: rgba(255, 255, 255, 0.1); /* Adjust the background color and opacity as needed */
    box-shadow: 0 0 30px rgba(0, 0, 0, 0.3);
    border-color: black;
}


#left{
    position: relative;
    width:60%;
    height:100%;
    background-color: rgb(170, 223, 231);
    
    
}

#right{
    width:40%;
    height:100%;
    background-color: rgb(255, 255, 255);
    display: flex;
    align-self: start;
    justify-content: center;
}



#lnav{
    display:flex;
    width:100%;
    padding:20px 30px;
    justify-content: space-between;
}

#lnav1 a{
    margin-right: 20px;
    text-decoration: none;
    color: black;
     font-weight: 500;
     font-size: 20px;
}

#left #text{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%); 
}

#text h1{
    font-size: 90px;
    font-weight: 900;
    color: rgb(3, 3, 3);
}

#text p{
    opacity: 0.6;
    font-size: 12px;
    line-height: 20px;
    margin-top: 20px;
    margin-bottom: 20px;
}

#text a.{
    text-decoration: none;
    color: rgb(255, 255, 255);
    padding-bottom: 5px;
    font-size: 15px;
     font-weight: 500;
}
#right img {
      width: 80%;
      height: 100%;
      object-fit: cover;
      border-radius: 50%;
      display:flex;
    }
 /* Style to make the link look like a button */
 a {
      display: inline-block;
      padding: 10px 20px; /* Adjust padding as needed */
      text-decoration: none;
      background-color: #000000; /* Green color, you can change this */
      color: #f0f8f1; /* White text */
      border: 1px solid #ffffff; /* Border color matches background color */
      border-radius: 5px; /* Rounded corners */
      transition: background-color 0.3s ease; /* Smooth transition on hover */
    }

    /* Hover effect */
    a:hover {
      background-color: #ffffff; /* Darker green on hover, adjust as needed */
      color: #000;
    }


    </style>
</head>
<body>
    <div id="main">
    <div id="left">
        <div id="lnav">
            <i class="ri-arrow-left-line"></i>
            <div id="lnav1">
                
                
                
                
            </div>
            <div id="text">
                <h1>Hello,</h1>
                <p>Greetings! I'm Prakruthi, a passionate and creative individual with a love for web development and design. 
			With a keen eye for detail and a dedication to crafting visually appealing and functional websites, I bring a unique blend of technical skills and artistic flair to every project. My journey in the world of coding began with HTML and CSS, and over time, I've delved into the realms of JavaScript and various web development frameworks. Beyond the lines of code, I am driven by a constant desire to learn and explore new technologies, ensuring that I stay at the forefront of the ever-evolving digital landscape. When I'm not immersed in coding, you can find me experimenting with design concepts, enjoying a good cup of coffee, or exploring the latest trends in the tech world. Let's connect and explore the endless possibilities of the web together!</p>
                     When I'm not immersed in coding, you can find me experimenting with design concepts, enjoying a good cup of coffee, or exploring the latest trends in the tech world. Let's connect and explore the endless possibilities of the web together!</p>
                <a href="r.html">Start</a>
            
            </div>

        </div>
    </div>
    <div id="right">
        
        <div class="p-5"><img class="img-fluid rounded-circle" src="prakruthi.PNG" alt="..." /></div>
                
    </div>
</div>

    
</body>
</html>
