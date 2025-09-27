# Ex04 Places Around Me
## Date: 27.09.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html
<html>
    <head>
        <title>
            Map-Kanniyakumari
        </title>
    </head>
    <body>
        <h1 style="color:red" align="center">Kanyakumari-city</h1>
        <h4 align="center" style="color: blue;">Iswarya-S(25016326)</h4>
        <HR>
        <img src="map.png" usemap="#image-map" align="center">
        <map name="image-map">
            <area target="" alt="kanniyakumari beach" title="kanniyakumari beach" href="beach.html" coords="1067,231,916,188" shape="rect">
            <area target="" alt="open from 4 a.m to 6 a.m" title="open from 4 a.m to 6 a.m" href="sunrise.html" coords="924,451,960,463,1001,459,1045,463,1048,478,1028,487,995,488,950,485,928,491,899,487,897,460,908,453"  shape="poly">
            <area target="" alt="temple" title="temple" href="temple.html" coords="760,695,81" shape="circle">
            <area target="" alt="--6590" title="--6590" href="hotel.html" coords="605,33,784,108" shape="rect" target="_blank">
            <area target="" alt="railway junction" title="railway junction" href="rail.html" coords="326,151,464,108" shape="rect">
        </map>
        
    </body>
</html>

beach.html

<html>
    <head>
        <title>
            KANNIYAKUMARI BEACH-KANNIYAKUMARI CITY
        </title>
    </head>
    <body bgcolor="lightblue" >
        <h1 align="center" style="color: rgb(103, 84, 56);">KANNIYAKUMARI-CITY</h1>
        <h4 align="center" style="color: rgb(68, 67, 65);">Kanniyakumari Beach</h4>
        <hr>
        <p style="margin: 15px; font-size: 28 "><b>
            Here is where you can see the confluence of three major water bodies that in many ways define this uniqueness – the Bay of Bengal, the Indian Ocean and the Arabian Sea.
        </b></p>
    </body>
</html>

temple.html

<html>
    <head>
        <title>
            Arulmigu Devi Kanniyakumari temple
        </title>
        <style>
            body{
                background-color: brown;
            }
        </style>
    </head>
    <body>
        <h1 align="center" style="color: rgb(234, 203, 156);">KANNIYAKUMARI-CITY</h1>
        <h4 align="center" style="color: rgb(216, 211, 200);">Arulmigu Devi Bagavathi Temple</h4>
        <hr>
        <p style="margin: 15px; color: aliceblue; font-size: 28 " ><b>
            The Kumari Amman Temple, also known as the Bhagavathi Amman Temple, is a 3,000-year-old sacred site in Kanyakumari dedicated to the virgin goddess Devi Kanyakumari, one of the 108 Shakti Peethas
        </b></p>
    </body>    
</html>

rail.html

<html>
    <head>
        <title>
            Kanniyakumari Railway Junction
        </title>
        <style>
            body{
                background-color: rgb(145, 175, 161);
            }
        </style>
    </head>
    <body>
        <h1 align="center" style="color: rgb(234, 203, 156);">KANNIYAKUMARI-CITY</h1>
        <h4 align="center" style="color: rgb(216, 211, 200);">Kanniyakumari Railway station</h4>
        <hr>
        <p style="margin: 15px; color: aliceblue; font-size: 28 " ><b>
            Avaliable 24 hours with minimal Amenities. Railway services in Kanniyakumari.
        </b></p>
    </body>    
</html>

sunrise.html

<html>
    <head>
        <title>
            Sunrise point
        </title>
        <style>
            body{
                background-color: rgb(239, 122, 38);
            }
        </style>
    </head>
    <body>
        <h1 align="center" style="color: rgb(240, 211, 169);">KANNIYAKUMARI-CITY</h1>
        <h4 align="center" style="color: rgb(216, 211, 200);">Sunrise Point</h4>
        <hr>
        <p style="margin: 15px; color: aliceblue; align-items: center; font-size: 28 " ><b>
            <img src="download.jpg" height="250">
            <br>
            Kanyakumari's unique geographical location at the confluence of the Arabian Sea, the Bay of Bengal, and the Indian Ocean makes the sunrise especially dramatic. The sun appears to emerge directly from the water, painting the sky with vibrant colors. 
        </b></p>
    </body>    
</html>

hotel.html

<html>
    <head>
        <title>
            Sunrise point
        </title>
        <style>
            body{
                background-color: rgb(15, 89, 150);
            }
        </style>
    </head>
    <body>
        <h1 align="center" style="color: rgb(240, 211, 169);">KANNIYAKUMARI-CITY</h1>
        <h4 align="center" style="color: rgb(205, 218, 226);">Hotel Singhaar International</h4>
        <hr>
        <p style="margin: 15px; color: aliceblue; align-items: center; font-size: 28 " ><b>
            <img src="Screenshot 2025-09-27 104512.png" height="250">
            <br>
            Hotel Singaar International is a hotel located in Kanyakumari, Tamil Nadu, with views of the Indian Ocean. It is situated on Main Road and is close to popular tourist spots like the Vivekananda Rock Memorial and Thiruvalluvar Statue. 
    </body>    
</html>
```

## OUTPUT
![alt text](<Screenshot (17).png>)
![alt text](<Screenshot (18).png>)
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (21).png>)
![alt text](Screenshot(9).png)
## RESULT
The program for implementing image maps using HTML is executed successfully.
