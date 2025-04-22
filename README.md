# Ex04 Places Around Me
# Date:18/04/2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
/* Developed By : YUVAN SHANKAR M
Reg No : 212224220126
*/
img.html
<html>
    <head>
        <title> Chennai </title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Chennai</b></font>
            </h1>
            <h3 align="center">
            <font color="blue"><b> RABI BASKAR PRABURAJAN [212224040257]</b></font> 
            </h3>
            <center>
                <style>
                    .image-fit {
                      width: 100%;           
                      height: 300px;         
                      object-fit: cover;  }
                  </style>
                  
                  <img src="C:\Users\admin\Desktop\env1\Chennai.png"  class="image-fit" alt="image">
                  <img src="Chennai.png" usemap="#image-map">

<map name="image-map">
    <area target="_blank" alt="Anna Nagar" title="Anna Nagar" href="Anna Nagar.html" coords="1237,508,1369,576" shape="rect">
    <area target="_blank" alt="Koyambedu" title="Koyambedu" href="Koyambedu.html" coords="1139,620,1271,673" shape="rect">
    <area target="_blank" alt="Nungambakkam" title="Nungambakkam" href="Nungambakkam.html" coords="1435,695,1612,759" shape="rect">
    <area target="_blank" alt="T . Nagar" title="T . Nagar" href="T . Nagar.html" coords="1405,798,1527,877" shape="rect">
    <area target="_blank" alt="Poonamallee" title="Poonamallee" href="Poonamallee.html" coords="485,777,597,821" shape="rect">
</map>
</center>


                  
    </body>
</html>

Poonamallee.html

<html>
    <head><title>Poonamallee</title></head>
    <style>
        *{background-image: url('Poonamallee img.jpg');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;}
        h1{
            text-align: center;
            color:black;
        }
        h2{
            text-align: center;
            color: orange;
        }
        h3{
            color:goldenrod
        }
    </style>
    <body >
        <h1>Chennai</h1>
        <h2>Poonamallee</h2>
        <hr color="black">
        <h3><p> <fieldset>
            Poonamallee is a fast-growing suburb on the western edge of Chennai, located along the Chennai–Bangalore Highway. Known for its historical landmarks like the Varadaraja Perumal Temple and the Big Mosque, it also holds cultural significance as the birthplace of saint Thirukachi Nambi. With its strategic location and improving infrastructure, Poonamallee is emerging as a key residential and commercial hub in the city.
        </body>
</html>

T . Nagar.html

<html>
    <head><title>T . Nagar</title></head>
    <style>
        *{background-image: url('T . Nagar img.jpg');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;}
        h1{
            text-align: center;
            color:black;
        }
        h2{
            text-align: center;
            color: orange;
        }
        h3{
            color:aliceblue
        }
        
    </style>
    <body >
        <h1>Chennai</h1>
        <h2>T . Nagar</h2>
        <hr color="black">
        <h3><p> <fieldset>
            T. Nagar (Thyagaraya Nagar) is one of Chennai’s busiest and most popular shopping districts, famous for its textiles, jewelry stores, and street shopping. It's a go-to destination during festivals and weddings, drawing crowds from all over the city and beyond. Apart from shopping, it’s also a well-developed residential and commercial area with excellent connectivity.
        </body>
</html>

Nungambakkam.html

<html>
    <head><title>Nungambakkam</title></head>
    <style>
        *{background-image: url('Nungambakkam img.webp');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;}
        h1{
            text-align: center;
            color:black;
        }
        h2{
            text-align: center;
            color: orange;
        }
        
    </style>
    <body >
        <h1>Chennai</h1>
        <h2>Nungambakkam</h2>
        <hr color="white">
        <h3 ><p> <fieldset color = "white">
            Anna Nagar is a well-planned residential and commercial neighborhood in Chennai, Tamil Nadu. Known for its wide roads, organized layout, and modern infrastructure, it is one of the city's upscale localities. The area features parks, schools, shopping centers, and cafes, making it a popular choice for families and professionals. The iconic Anna Nagar Tower Park is a key landmark, and the locality is well-connected by road and metro, offering both convenience and quality of life.
         </body>
</html>

Koyambedu.html

<html>
    <head><title>Koyambedu</title></head>
    <style>
        *{background-image: url('koyambedu img.webp');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;}
        h1{
            text-align: center;
            color:black;
        }
        h2{
            text-align: center;
            color: orange;
        }
        
    </style>
    <body >
        <h1>Chennai</h1>
        <h2>Koyambedu</h2>
        <hr color="black">
        <h3><p> <fieldset>
            Koyambedu is a major hub in Chennai, Tamil Nadu, best known for housing one of Asia's largest wholesale markets — the Koyambedu Wholesale Market Complex. It is also a key transport center with the Chennai Mofussil Bus Terminus (CMBT) and a metro station, making it a vital link for travel and trade. The area is always bustling with activity and serves as a gateway to various parts of the city and beyond.

        </body>
</html>

Anna Nagar.html

<html>
    <head><title>Anna Nagar</title></head>
    <style>
        *{background-image: url('Anna Nagar img.jpg');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;}
        h1{
            text-align: center;
            color:black;
        }
        h2{
            text-align: center;
            color: orange;
        }
        
    </style>
    <body >
        <h1>Chennai</h1>
        <h2>Anna Nagar</h2>
        <hr color="black">
        <h3><p> <fieldset>
            Anna Nagar is a well-planned residential and commercial neighborhood in Chennai, Tamil Nadu. Known for its wide roads, organized layout, and modern infrastructure, it is one of the city's upscale localities. The area features parks, schools, shopping centers, and cafes, making it a popular choice for families and professionals. The iconic Anna Nagar Tower Park is a key landmark, and the locality is well-connected by road and metro, offering both convenience and quality of life.
        </body>
</html>


```
# OUTPUT
# RESULT
The program for implementing image maps using HTML is executed successfully.
