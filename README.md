# Ex-04 Places Around Me
## Date: 

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
<html lang="en">
    <head>
    </head>
    <script>
        function coordinate(event)
        {
            let x = event.clientX;
            let y = event.clientY;
            document.getElementById("text1").value = x;
            document.getElementById("text2").value = y;
        }
    </script>
    <body>
        <img src="map.png" width="1000px" usemap="#MapNew" onmousemove="coordinate(event)"> <br>
        <MAP name="MapNew">
            <AREA shape="RECT" coords="84,384,104,418" href="https://www.zomato.com/chennai/cream-stone-ice-cream-anna-nagar-east"
            Title="Cream Stone">
            <AREA shape="RECT" coords="740,281,579,336" href="https://www.zomato.com/chennai/ibaco-anna-nagar-west"
            Title="Ibaco">
            <AREA shape="RECT" coords="185,368,211,397" href="https://www.zomato.com/chennai/arun-ice-creams-1-anna-nagar-east"
            Title="Arun Icecream">
            <AREA shape="RECT" coords="435,497,460,527" href="https://www.zomato.com/chennai/havmor-havfunn-ice-cream-anna-nagar-east"
            Title="Havmor">
            <AREA shape="RECT" coords="647,280,661,302" href="https://www.zomato.com/chennai/ibaco-anna-nagar-west"
            Title="Ibaco">
            <AREA shape="RECT" coords="809,371,827,385" href="https://www.zomato.com/chennai/strictly-desserts-anna-nagar-east"
            Title="Strictly Desserts">
        </MAP>
        x Co-ordinate <input type="text" name="" id="text1" style="font-size:medium;"><br>
        y Co-ordinate <input type="text" name="" id="text2" style="font-size: medium;">
    </body>            
</html>
```

## OUTPUT

![image](https://github.com/pradeepasri26/NearMe/assets/131433142/dfc1dfaf-d81a-4bc6-bfe2-ceb60fdcc8d9)

![image](https://github.com/pradeepasri26/NearMe/assets/131433142/9efd21d6-bc96-442a-97c2-87d8fc49bc73)

## RESULT
The program for implementing image maps using HTML is executed successfully.
