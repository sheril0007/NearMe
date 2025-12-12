# Ex04 Places Around Me
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
map.html
```
<html>
<head>
<title>My city</title>
</head>
<body>
<h1 style ="text-align: center;">
    <b>Tiruvannamalai</b>
</h1>
<h3 style ="text-align: center;">
<b>SHERIL P (25012800)</b>
</h3>
<center>
<img src="map.jpg" usemap="#Mycity">
<map name="Mycity">
<area target="" alt="polur" title="polur" href="polur.html" coords="365,158,470,219" shape="rect">
<area target="" alt="kalasapakkam" title="kalasapakkam" href="kalasapakkam.html" coords="243,520,401,568" shape="rect">
<area target="" alt="kunnathur" title="kunnathur" href="kunnathur.html" coords="409,61,532,107" shape="rect">
<area target="" alt="karaipoondi" title="karaipoondi" href="karaipoondi.html" coords="508,186,642,233" shape="rect">
<area target="" alt="villvarani" title="villvarani" href="villvarani.html" coords="26,473,159,522" shape="rect">
</map>
</center>
</body>
</html>
```
polur.html
```
<html>
<head>
<title>polur</title>
</head>
<body bgcolor="skyblue">
<h1 align ="centre">
<front colour="red"><b>POLUR</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="polur" size="5">
    Polur is a historic town in Tamil Nadu known for its religious significance and vibrant culture. 
    It is located at the foot of the Javadi Hills and is home to the famous Arunachalaeshwarar temple.
    Polur is also a transport and trade hub for nearby villages.
</font>
</p>
</body>
</html>
```
kalasapakkam.html
```
<html>
<head>
<title>kalasapakkam</title>
</head>
<body bgcolor="yellow">
<h1 align ="centre">
<front colour="red"><b>KALASAPAKKAM</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="kalasapakkam" size="5">
    Kalasapakkam is a serene town located south of Polur, known for its agricultural background and peaceful surroundings. The town lies along the Cheyyar River, providing fertile lands and scenic views. It’s a calm and beautiful location away from city life.</font>
</p>
</body>
</html>
```
kunnathur.html
```
<html>
<head>
<title>kunnathur</title>
</head>
<body bgcolor="purple">
<h1 align ="centre">
<front colour="red"><b>KUNNATHUR</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="kunnathur" size="5">
    Kunnathur is a small village near Polur known for its green fields and rural charm. It is surrounded by small water bodies and is mainly inhabited by farmers. It serves as a quiet escape for those looking for natural beauty and simplicity.
</font>
</p>
</body>
</html>
```
karaipoondi.html
```<html>
<head>
<title>karaipoondi</title>
</head>
<body bgcolor="pink">
<h1 align ="centre">
<front colour="red"><b>KARAIPOONDI</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="karaipoondi" size="5">
    Karaipoondi is a village to the east of Polur, famous for its paddy fields and traditional Tamil lifestyle. The community is close-knit, and festivals are celebrated with great enthusiasm. The calm village roads and clear skies make it a scenic spot.
</font>
</p>
</body>
</html>
```
vilvarani.html
```
<html>
<head>
<title>villvarani</title>
</head>
<body bgcolor="orange">
<h1 align ="centre">
<front colour="red"><b>VILLVARANI</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="villvarani" size="5">        
    Villvarani is a peaceful village located southwest of Polur. It is known for its friendly residents and its natural beauty. With access to local farming lands and traditional houses, it gives a true picture of Tamil Nadu's rural life.
</font>
</p>
</body>
</html>
```
## OUTPUT
![1](https://github.com/user-attachments/assets/578a3565-1389-4d1c-b60b-fc18af38c992)
<img width="1035" height="143" alt="image" src="https://github.com/user-attachments/assets/7842ef4e-664f-4101-a2fc-631d8775b592" />
<img width="1032" height="152" alt="image" src="https://github.com/user-attachments/assets/01213b6f-ff00-44fa-909c-e5d070dc57d3" />
<img width="1031" height="155" alt="image" src="https://github.com/user-attachments/assets/c18260ef-3bf5-4d4b-bbc2-3eb9a8281eb9" />
<img width="1031" height="157" alt="image" src="https://github.com/user-attachments/assets/802a3ba5-709c-4357-a5e0-a1cc96ab7aea" />
<img width="1035" height="148" alt="image" src="https://github.com/user-attachments/assets/001c50a7-c8ec-4bcb-ae13-da6aa13e4f61" />
## RESULT
The program for implementing image maps using HTML is executed successfully.
