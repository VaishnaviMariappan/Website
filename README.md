# EXP 02 - CREATING A COMMERCIAL WEBSITE USING HTML & CSS
## AIM:

To create a commercial website using html and css.

## SOFTWARE:

Visual Studio Code.

## ALGORITHM:

1) Create a new HTML file and save it with a .html extension.Begin with the basic structure by adding the <!DOCTYPE html> declaration at the top.
2) Set up the Head:

       Inside the <head> element, add the <title> element and give it a meaningful title for your website.
       Link your CSS file by adding the <link> element with the rel attribute set to "stylesheet" and 
       the href attribute pointing to your CSS file.

3) Develop the Content:

        Divide the main content area into sections using appropriate HTML elements like <section>, <div>, or <article>.
        Use headings <h1> to <h6> to structure your content hierarchically.
        Incorporate text, images, videos, and other media within the content sectionS


4) Style with CSS:
 
  Create a new CSS file and save it with a .css extension.
  Select the elements you want to style using CSS selectors.
  Apply styles using properties and values. 
  For example, you can change colors, fonts, sizes, margins, and padding.

5) Find a web hosting provider to host your website online.
Upload your HTML, CSS, and any other necessary files to the hosting server.

6) Test your website again after deployment to ensure it works as intended.
  
## PROGRAM:
  
### HTML CODE:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="Stylesheet" href="style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
</head>
<body>
    <div>
        <img src="signal.png" alt="photo" height="35px" width="35px">
        <div class="menu"><a href="offerings.html">Offerings</a></div>
        <div class="menu"><a href="stories.html">Stories</a></div>
        <div class="menu"><a href="help.html">Help</a></div>
        <button class="login">login</button>
    </div>
    <br>
    <div class="left">
    <h1>
        Explore the life you want to live.<br>Put your money to work
    </h1>
    <button class="but">Get in touch</button>
</div>

    <div class="images">
        <img src="medal.png" alt="photo" height="75px" width="55px"><img class = "img"src="chip.png" alt="photo" height="100px" width="80px"><img class = "img"src="ai1.png" alt="photo" height="85px" width="120px">
    </div>
    <div>
        <p style="margin-left: 10%;">&emsp;&emsp;&emsp;&emsp;&emsp;Financial expertise&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Advanced Technology&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Right &nbsp;Advice</p>
    </div>
    <p class = "text">Astrology lights the path known as life and it is entirely our choice as to whether we want to travel on this path or not.<br>Astrology helps us to know how we can make the best possible use of these tools in our lives<br>for our benefit when we see the bad phase in our lives.<br>Astrology is the connecting chord among our past, present and future.<br><br>It knows no caste, religion, gender or nationality.<br>It simply concerns the important fundamentals of our everyday lives.</p>
    <img class="hehe" align = "right" src="cons.png" alt="photo" height="450px" width="900px">
    <p class="title">Analysis of your wealth</p>
    <h2>Helping you connect the dots.<br>So you can see what life could look like into the future.</h2>
    <p style="margin-left: 40px; font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 17px;">A horoscope is a Cosmic Map derived from our time of birth and reveals our unalterable past and probable future.<br>
        A horoscope in astrology holds answers to our past lives' Karmic structure and to analyse the results in this life.</p>
</body>
</html>
```
      

### CSS CODE:
```css      
body{
    background-image:url(image1.png);
    background-size: 100%;
}
h1{
    color: rgb(230, 205, 235);
    font-size:35px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
h2{
    color:rgb(230, 205, 235);
    font-family:Georgia, 'Times New Roman', Times, serif;
    margin-left: 5%;
    font-size:30px;
}
.title
{
    margin-top: 7%;
    color: rgb(124, 3, 176);
    font-family:Arial, Helvetica, sans-serif;
    margin-left: 5%;
    text-align:left;
    margin-top: 33%;
    font-size: 20px;
}
.but
{
    background-color: rgb(104, 57, 136);
    color: rgb(246, 244, 248);
    width: 135px;
    height:35px;
    border-radius: 25px;
    border-color: rgb(229, 203, 247);
    margin-top: 2%;
}
.login
{
    border-color: rgb(109, 51, 125);
    width: 100px;
    height:30px;
    border-radius: 25px;
    color:rgb(246, 244, 248);
    background-color:transparent;
    position: absolute;
    border-color: rgb(219, 185, 244);
    right: 77px;
    margin-top: 18px;
}
.text
{
    text-align:right;
    position: absolute;
    right:30px;
    margin-top: 7%;
    font-size:20px;
    color: rgb(215, 208, 220);
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
p
{
    font-size: 20px;
    color:rgb(215, 208, 220);
}   
.menu
{
    display: inline-block;
    margin-left: 100px;
    margin-right: 25px;
    margin-top: 0px;
}
a{
    color: rgb(215, 208, 220);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif ;
}
.left
{
    position: absolute;
    left: 17%;
    margin-top: 4%;
}
.hehe
{
    margin-top: 35%;
}
.img
{
    padding-left:200px;;
}
.images
{
    margin-left: 20%;
    margin-top: 17%;
}
```
 
## OUTPUT
![website](https://github.com/VaishnaviMariappan/Website/assets/94169913/aea7ba73-32b1-4c1b-870a-e1f314b0abe5)


## RESULT:
      
Thus the website is created.
