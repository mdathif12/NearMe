# Ex04 Places Around Me
## Date: 29/4/2024

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
      <title>CHENNAI</title>
    </head>
    
    <body>
      <h1 align="center">
        <font color="black"><b>CHENNAI</b></font>
      </h1>
      <h2 align="center">
        <font color="black"><b>S.KEERTHIVASAN(212222040076)</b></font>
      </h2>
    
    <center>
       
        <img src="bessy.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="marina beach" title="marina beach" href="marina.html" coords="1428,69,1508,322" shape="rect">
    <area target="" alt="bessy" title="bessy" href="bessy.html" coords="1345,539,1414,698" shape="rect">
    <area target="" alt="chennai international airport" title="chennai international airport" href="airport.html" coords="362,604,688,657,429,814" shape="poly">
    <area target="" alt="santhome cathedral basilica church" title="santhome cathedral basilica church" href="santhome.html" coords="1415,358,50" shape="circle">
    <area target="" alt="guindy national park" title="guindy national park" href="park.html" coords="875,543,977,750,1156,576" shape="poly">
</map>
    
    </map>
    </center>
    </body>
    
</html>
marina.html
<html>
    <head>
        <title>MARINA BEACH</title>
        <h1 align="center">CHENNAI<h1>
         <h2 align="center" style="color:black;">MARINA BEACH<h2>   
<hr style="height:10px;background-color:white;width:100%">

    </head>
 <body bgcolor="green"> 
    <br>   
    <P align="center"> 
        Marina Beach, or simply the Marina, is a natural urban beach in Chennai, Tamil Nadu, India, along the Bay of Bengal. The beach runs from near Fort St. George in the north to Foreshore Estate in the south, a distance of 6.0 km, making it the second longest urban beach in the world, after Cox's Bazar Beach.  </p>    


</html>
bessy.html
<html>
    <head>
        <title>BESANT NAGAR</title>
        <h1 align="center">CHENNAI<h1>
         <h2 align="center" style="color:black;">BESANT NAGAR<h2>   
<hr style="height:10px;background-color:white;width:100%">

    </head>
 <body bgcolor="red"> 
    <br>   
    <P align="center"> 
        Edward Elliot's Beach, simply called as Elliot's Beach and popularly known as Besant Nagar Beach or the Bessie, is a natural urban beach located in the Besant Nagar neighbourhood of Chennai, Tamil Nadu, India.   </p>    


</html>
airport.html
<html>
    <head>
        <title>Chennai International Airport</title>
        <h1 align="center">CHENNAI<h1>
         <h2 align="center" style="color:black;">Chennai International Airport<h2>   
<hr style="height:10px;background-color:white;width:100%">

    </head>
 <body bgcolor="blue"> 
    <br>   
    <P align="center"> 
        Chennai International Airport is an international airport serving the city of Chennai, the capital of Tamil Nadu, India and its metropolitan area. It is located in Tirusulam, around 20 km southwest of the city centre. The airport is the fifth-busiest airport in India, and third by international traffic. </p>    


</html>
santhome.html
<html>
    <head>
        <title>San Thome Church</title>
        <h1 align="center">CHENNAI<h1>
         <h2 align="center" style="color:black;">San Thome Church<h2>   
<hr style="height:10px;background-color:white;width:100%">

    </head>
 <body bgcolor="cyan"> 
    <br>   
    <P align="center"> 
        
San Thome Church, officially known as St Thomas Cathedral Basilica and National Shrine of Saint Thomas, is a minor basilica of the Catholic Church in India, at the Santhome neighbourhood of Chennai, in Tamil Nadu.

   </p>    


</html>
park.html
<html>
    <head>
        <title>Guindy National Park</title>
        <h1 align="center">CHENNAI<h1>
         <h2 align="center" style="color:black;">Guindy National Park<h2>   
<hr style="height:10px;background-color:white;width:100%">

    </head>
 <body bgcolor="yellow"> 
    <br>   
    <P align="center"> 
        Guindy National Park is a 2.70 km2 (1.04 sq mi) protected area of Tamil Nadu, located in Chennai, India, is the 8th-smallest National Park of India and one of the very few national parks situated inside a city. The park is an extension of the grounds surrounding Raj Bhavan, formerly known as the 'Guindy Lodge', the official residence of the governor of Tamil Nadu, India. It extends deep inside the governor's estate, enclosing beautiful forests, scrub lands, lakes and streams.   </p>    


</html> 

```

## OUTPUT
![Screenshot 2024-04-29 090814](https://github.com/keerthivasan50/NearMe/assets/150429883/b65f8b07-9acf-4627-b957-a4a90faac46e)
![Screenshot 2024-04-29 091642](https://github.com/keerthivasan50/NearMe/assets/150429883/9124a459-901a-4d0b-abab-f1e0c21c4fdf)
![Screenshot 2024-04-29 091711](https://github.com/keerthivasan50/NearMe/assets/150429883/2e953b1d-ef61-4237-b68d-f1d61e9a1f36)
![Screenshot 2024-04-29 091730](https://github.com/keerthivasan50/NearMe/assets/150429883/f52e113d-2905-41e9-8834-bdb9b53ca168)
![Screenshot 2024-04-29 091811](https://github.com/keerthivasan50/NearMe/assets/150429883/a531a22b-4a90-484f-9be2-fe77c6b9714a)
![Screenshot 2024-04-29 091819](https://github.com/keerthivasan50/NearMe/assets/150429883/9379f6d9-fa7e-47dc-bc52-75c22addc4c1)








## RESULT
The program for implementing image maps using HTML is executed successfully.
