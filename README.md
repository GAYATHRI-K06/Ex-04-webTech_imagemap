# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1
create a folder "static" under the project folder "mapping".

## Step 2
in static,create a file "map.html".

## Step 3
go to google maps and take screenshot of your home along with 5 places around it

## Step 4
go to image-maps.com and make 5 locations on it using the shapes used in maps.

## Step 5
copy the code and add it into "map.html"

## Step 6
create the html documents to be displayed when clicked on the location in image map.

## Step 7
take screenshot of the output

# Code:

## map.html
````
<body>
<h1 align="center">
<fontcolor="red"><b>poonamallee</b></font>
</h1>
<h3 align="center">
<fontcolor="blue"><b>gayathri.k (23013439)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">

<mapname="MyCity">
    
<area target="" alt="dmart" title="dmart" href="shopping.html" coords="974,442,1081,496" shape="rect">
<area target="" alt="panimalar medical collage" title="panimalar medical collage" href="collage.html" coords="182,265,392,306" shape="rect">
<area target="" alt="sri kamachi amman temple" title="sri kamachi amman temple" href="temple.html" coords="754,672,969,733" shape="rect">
<area target="" alt="apollo hospital" title="apollo hospital" href="hospital.html" coords="1411,20,1602,71" shape="rect">
<area target="" alt="fab hotel" title="fab hotel" href="hotel.html" coords="1560,170,1693,199" shape="0">


</map>
</center>
</body>
 </html>
````

## collage.html
````
<html>
    <head>
        <title>collage</title>
    </head>
    <body style="background-color: pink; color: black; text-align: center;">
        <h1 style="font-size: 100px;">panimalar medical collage<b></b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; Panimalar Medical College Hospital & Research Institute is a Christian Minority Institution of Higher Education</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733;  governed by the “Jaisakthi Educational Trust”, Chennai. .</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733; Trust aims atimparting quality engineering, medical, nursing and other health professions education for the aspiring youth.</li>
        </ul>
    </body>
</html>
````
## hospital.html
````
<html>
    <head>
        <title>hospital</title>
    </head>
    <body style="background-color: greenyellow; color: black; text-align: center;">
        <h1 style="font-size: 100px;">apollo hospital<b></b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733;Deliver High Quality Medical Treatment & Warm Healing Experience for Our Patients.</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733;  Apollo Hospitals Enterprise Limited is an Indian multinational healthcare group headquartered in Chennai.</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733;Apollo Hospital share price was Rs 5,466.80 as on 21 Nov, 2023,</li>
        </ul>
    </body>
</html>
````
## hotel.html
```
<html>
    <head>
        <title>hotel</title>
    </head>
    <body style="background-color:orangered; color: black; text-align: center;">
        <h1 style="font-size: 100px;">fab hotel<b></b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; Conveniently located in the Thoraipakkam district of Chennai</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733;  FabHotel Sasti Inn is located 5.1 miles from Indian Institute of Technology, Madras, 6..</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733; FabHotels is a network of 3 star budget hotels in India,</li>
        </ul>
    </body>
</html>
```
## shopping.html
````
<html>
    <head>
        <title>shopping</title>
    </head>
    <body style="background-color: maroon; color: white; text-align: center;">
        <h1 style="font-size: 100px;"><b>dmart</b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; Min. 7%* Off on Groceries, Dairy & Beverages, Packaged Foods, Personal Care, Home & Kitchen, Stationery & Much More</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733;  It was founded by Radhakishan Damani in 2002 when its first store was opened in Powai, Mumbai.</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733; it has 330 stores across 14 states in India.</li>
        </ul>
    </body>
</html>
````

## temple.html
````
<html>
    <head>
        <title>temple</title>
    </head>
    <body style="background-color: blue; color: white; text-align: center;">
        <h1 style="font-size: 100px;">sri kamachi amman templee<b></b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; The Sri Kamakshi Amman Temple is an ancient Hindu Temple dedicated to the goddess Kamakshi</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733;  The Kamakshi Amman Temple is known for its religious significance, stunning architecture, and rich history</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733; Dedicated to Goddess Kamakshi, a divine form of Goddess Parvati, the temple holds immense spiritual importance for devotees.</li>
        </ul>
    </body>
</html>
````
# Output:

![Screenshot 2023-11-22 125405](https://github.com/GAYATHRI-K06/Ex-04-webTech_imagemap/assets/145742742/af241244-e5ba-49b1-9c06-0fa48b324a07)

![Screenshot 2023-11-22 130331](https://github.com/GAYATHRI-K06/Ex-04-webTech_imagemap/assets/145742742/b027418d-e06d-41e5-b00d-c5b49bec72d9)

![Screenshot 2023-11-22 130653](https://github.com/GAYATHRI-K06/Ex-04-webTech_imagemap/assets/145742742/4e2aa9ee-c577-4ae9-80fa-b5467504b48f)

![Screenshot 2023-11-22 124850](https://github.com/GAYATHRI-K06/Ex-04-webTech_imagemap/assets/145742742/e517b3b4-b552-4f3f-b14b-0946f13a9585)

![Screenshot 2023-11-22 125836](https://github.com/GAYATHRI-K06/Ex-04-webTech_imagemap/assets/145742742/9812d65e-29ac-461d-b53e-d295b0e06d6f)

## result
The output was verified successfully
