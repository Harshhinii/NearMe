# Ex04 Places Around Me
## Date: 18-03-2024

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
map.html
```
<html>
    <head>
        <title>kanchipuram</title>
    </head>
    <body bgcolor="cyan">
        <h1> KANCHIPURAM CITY </h1>
        <h3>Name: harshini R</h3>
        <h3>Reg no: 212223220033</h3>
<img src="map..png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="babu cinemas" title="babu cinemas" href="babucinemas.html" coords="963,244,68" shape="circle">
    <area target="" alt="SVM School" title="SVM School" href="svm school.html" coords="815,643,54" shape="circle">
    <area target="" alt="A.S.BABU SAH" title="A.S.BABU SAH" href="a s babu sah.html" coords="1123,169,59" shape="circle">
    <area target="" alt="Vishali Mahal" title="Vishali Mahal" href="vishali mahal.html" coords="717,552,64" shape="circle">
    <area target="" alt="Sevlimedu" title="Sevlimedu" href="Sevlimedu.html" coords="625,722,61" shape="circle">
</map>
    </body>
</html>
```
sevlimedu
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
        <font color="gold"><b>KANCHIPURAM CITY</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>sevlimedu</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
        <font face="Georgia" size="5">
            Sevilimedu is a part of kanchipuram city in Tamil Nadu, India. Sevilimedu. city. Sevilimedu is located in Tamil Nadu. Sevilimedu
        </font>
        </p>
    </body>
</html>
```
vishali.mahal.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="red">
        <h1 align="center">
        <font color="gold"><b>KANCHIPURAM CITY</b></font>
        </h1>
        <h3 align="center">
        <font color="geen"><b>vishalimahal</b></font>
        </h3>
        <hr size="3" color="violet">
        <p align="justify">
        <font face="Georgia" size="5">
            Vishali Thirumana Mandapam in Gem Nagar,Kanchipuram listed under Banquet Halls in Kanchipuram. 
        </font>
        </p>
    </body>
</html>
```
a s babu sah.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>KANCHIPURAM CITY</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>asbabusah</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
        <font face="Georgia" size="5">
            A.S.Babu Sah offers you a delightfully rich collection of both traditional and fashionable silk sarees
        </font>
        </p>
    </body>
</html>
```
svm school.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
        <font color="gold"><b>KANCHIPURAM CITY</b></font>
        </h1>
        <h3 align="center">
        <font color="orange"><b>svmschool</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
        <font face="Georgia" size="5">
            This stands as a modern institution serving the best education to the society in the village of Sevilimedu, Kanchipuram District. Facilities
        </font>
        </p>
    </body>
</html>
```
babucinemas.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="red">
        <h1 align="center">
        <font color="gold"><b>KANCHIPURAM CITY</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>babu cinemas</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
        <font face="Georgia" size="5">
            A.S.Babu Sah offers you a delightfully rich collection of both traditional and fashionable silk sarees
        </font>
        </p>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-03-27 123056.png>) ![alt text](<Screenshot 2024-03-27 123108.png>) ![alt text](<Screenshot 2024-03-27 123520.png>) ![alt text](<Screenshot 2024-03-27 123531.png>) ![alt text](<Screenshot 2024-03-27 123542.png>) ![alt text](<Screenshot 2024-03-27 123609.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
