# Ex04 Places Around Me
## Date:28.09.2025 

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
        <title>city</title>
    </head>
  <body>
    <h1 align="center">PERAMBALUR</h1>
    <img src="Screenshot (17).png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="hotal subha residency" title="hotal subha residency" href="hotel.html" coords="1035,573,1508,657" shape="rect">
    <area target="" alt="hotel guru perambalur" title="hotel guru perambalur" href="guru.html" coords="276,351,734,349,785,518,310,542" shape="poly">
    <area target="" alt="rakesh park inn" title="rakesh park inn" href="park.html" coords="1225,679,1573,759" shape="rect">
    <area target="" alt="genuine carz" title="genuine carz" href="carz.html" coords="476,203,130" shape="circle">
    <area target="" alt="SJ residency" title="SJ residency" href="residency.html" coords="1456,173,1727,176,1761,305,1584,368,1368,308,1276,241" shape="poly">
</map>
  </body>
</html> 

park.html

<html>
    <head>
        <title>hotel</title>
    </head>
    <body>
        <h1 align="center">rakesh inn</h1>
        <p>NAME:rakesh park inn
LOCATION:NO. 57G,(SF NO. 29/6),near banana leaf restaurant,thuraimangalam,Main Road,Perambalur,Tamil Nadu,621220
FACILITIES AND PRICING:they offer different room type (single non AC,double non AC,deluxe,suite)with starting from $700 per day for basic non -AC to higher for AC/deluxe
        </p>
    </body>
</html>   

residency.html

<html>
    <head>
    <title>S.J residency</title>
    </head>
<body bgcolor="red">
    <h1 align=center>S.J. residency</h1>
    <p>
        NAME:S.J residency.
    </p>
    <p>
       ADDRESS:on NH-45(Chennai Trichy highway),perambalur,PIN 621212.
    </p>
    <p>
       CONTACT NO:950052752   
    </p>
    <p>
       rooms are generally clean and reasonably comfortable.
    </p>
    <p>
      staff behaviour is often praised.
</body>
</html>

carz.html

<html>
    <head>
    <title>hotel</title>
    </head>
<body bgcolor="yellow">
    <h1 align=center>Genuine carz</h1>
    <p>
         TYPE OF BUSSINESS:second-hand car dealer.
    </p>
    <p>
       ADDRESS:elambalur Road New bus stand road,Perambalur-near raja cinemas.  
    </p>
    <p>
       RATING:on justdial,currently show "0 Ratings"for genuine Carz    
    </p>
</body>
</html>

guru.html

<html>
    <head>
    <title>hotel</title>
    </head>
<body bgcolor="blue">
    <h1 align=center>guru</h1>
    <p>
         NAME:Hotel Guru
    </p>
    <p>
         ADDRESS:M V K nagar,near Old Bus Stand,New Bus Stand Road ,Perambalur,Tamil Nadu-PIN 621212
    </p>
    <p>
          CONTACT NO:9500882143
    </p>
    <p>
          EMAIL:hotelguruperambalur@gmail.com
    </p>
</body>
</html>

hotel.html

<html>
    <head>
        <title>subha</title>
    </head>    
        <body bgcolor="green">
            <h1 align="center">SUBHA RESIDENCY</h1>
            <P>NAME:Subha residency</P>
            <p> ADDRESS:subha residency ;SH 142 Thuraimangalam Perambalur ,Tamil Nadu,621212</p>
            <p>CONTACT:8270525525</p>
            <p>RATING:about 3.7/5 on site like google Maps</p>
            <p>ROOM TYPE AND PRICING:standard AC rooms type,deluxe,suits etc</p>
        </body>
</html>

```

## OUTPUT

![alt text](<Screenshot (24)-1.png>) 
![alt text](<Screenshot (25)-1.png>) 
![alt text](<Screenshot (26)-1.png>)
![alt text](<Screenshot (27)-1.png>)
![alt text](<Screenshot (28)-1.png>)
![alt text](<Screenshot (29)-1.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
