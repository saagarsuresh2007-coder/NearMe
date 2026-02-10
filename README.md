# Ex03 Places Around Me
## Date: 10.01.2026

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html
<html>
    
    <body align ="center" >
        <H1>CHENNAI-KOYAMBEDU</H1>
        <h3>Saagar S (25013937)</h3>
        <img src="Screenshot 2026-02-09 090024.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Market" title="Market" href="market.html" coords="1022,575,856,436" shape="rect">
    <area target="" alt="Metro" title="Metro" href="metro.html" coords="1069,286,78" shape="circle">
    <area target="" alt="Rohini Silver Screens" title="Rohini Silver Screens" href="rohini.html" coords="1093,100,46" shape="circle">
    <area target="" alt="Temple" title="Temple" href="temple.html" coords="1180,258,1187,333,1345,341,1350,291,1343,244,1267,238,1201,228" shape="poly">
    <area target="" alt="Radiance" title="Radiance" href="apartment.html" coords="745,257,737,289,739,318,753,344,792,345,800,321,797,284,779,258,761,257" shape="poly">
    
</map>
    </body>
</html>

temple.html
<html>
    <head>
        <title>KURUNGALEESHVARAR TEMPLE</title>
    </head>
    <body bgcolor="yellow" align="center">
        <h1>CHENNAI-KOYAMBEDU</h1>
        <h2>KURUNGALEESHVARAR TEMPLE</h2>
        <p>Located in Koyambedu, KURUNGALEESHVARAR TEMPLE is an old temple and many people come to visit in weekends </p>
        
    </body>
</html>

rohini.html
<html>
    <head>
        <title>ROHINI SILVER SCREENS</title>
    </head>
    <body bgcolor="blue" align="center">
        <h1>CHENNAI-KOYAMBEDU</h1>
        <h2>ROHINI SILVER SCREENS</h2>
        <p>Located in Koyambedu, Rohini Silver Screens is more than just a cinema; it’s a high-energy "fan fort" where the roar of the crowd is often louder than the speakers during a big star's release.</p>
        
    </body>
</html>

metro.html
<html>
    <head>
        <title>KOYAMBEDU METRO</title>
    </head>
    <body bgcolor="red" align="center">
        <h1>CHENNAI-KOYAMBEDU</h1>
        <h2>KOYAMBEDU METRO</h2>
        <p>Located in Koyambedu, it is the most used transport and it is most affordable transport</p>
        
    </body>
</html>

market.html
<html>
    <head>
        <title>KOYEMBEDU MARKET</title>
    </head>
    <body bgcolor="green" align="center">
        <h1>CHENNAI-KOYAMBEDU</h1>
        <h2>KOYEMBEDU MARKET</h2>
        <p>Located in Koyambedu, koyambedu market is most popular and it has every type of vegetables and fruits </p>
        
    </body>
</html>

apartment.html
<html>
    <head>
        <title>RADIANCE APPARTS</title>
    </head>
    <body bgcolor="cyan" align="center">
        <h1>CHENNAI-KOYAMBEDU</h1>
        <h2>RADIANCE APPARTS</h2>
        <p>Located in Koyambedu, it is the famous appartment in koyembedu where most of the celebrities live in</p>
        
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (15).png>) ![alt text](<Screenshot (17).png>) ![alt text](<Screenshot (18).png>) ![alt text](<Screenshot (16).png>) ![alt text](<Screenshot (20).png>) ![alt text](<Screenshot (21).png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
