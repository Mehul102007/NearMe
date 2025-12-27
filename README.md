# Ex04 Places Around Me
## Date: 27.12.2025
## ref number :25018961

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
~~~
<img src="Screenshot 2025-12-05 103801.png" usemap="#image-map">
<map name="image-map">
    <area target="" alt="VELLORE FORT" title="VELLORE FORT" href="fort.html" coords="84,416,331,485" shape="rect">
    <area target="" alt="GOVERNMENT MUSEUM" title="GOVERNMENT MUSEUM" href="museum.html" coords="138,594,350,683" shape="rect">
    <area target="" alt="CMC HOSPITAL" title="CMC HOSPITAL" href="cmc.html" coords="786,52,1006,111" shape="rect">
    <area target="" alt="OLD BUS STAND" title="OLD BUS STAND" href="oldbus.html" coords="413,278,662,355" shape="rect">
</map>
~~~
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vellore Fort</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #1d2671, #c33764);
            font-family: Arial, Helvetica, sans-serif;
        }

        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.15);
            padding: 25px;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
        }

        h1 {
            color: #ffffff;
            margin-bottom: 20px;
            letter-spacing: 2px;
        }

        img {
            width: 450px;
            max-width: 100%;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>VELLORE OLD BUS STAND</h1>
        <img src="download.jpg" alt="VELLORE OLD BUS STAND">
    </div>
</body>
</html>

~~~
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vellore Fort</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #1d2671, #c33764);
            font-family: Arial, Helvetica, sans-serif;
        }

        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.15);
            padding: 25px;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
        }

        h1 {
            color: #ffffff;
            margin-bottom: 20px;
            letter-spacing: 2px;
        }

        img {
            width: 450px;
            max-width: 100%;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>VELLORE CMC HOSPITAL</h1>
        <img src="cmc_hospital.jpg" alt="VELLORE CMC HOSPITAL">
    </div>
</body>
</html>

~~~
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vellore Fort</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #1d2671, #c33764);
            font-family: Arial, Helvetica, sans-serif;
        }

        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.15);
            padding: 25px;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
        }

        h1 {
            color: #ffffff;
            margin-bottom: 20px;
            letter-spacing: 2px;
        }

        img {
            width: 450px;
            max-width: 100%;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>VELLORE MUSEUM</h1>
        <img src="musume.jpg" alt="VELLORE MUSEUM">
    </div>
</body>
</html>

~~~
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vellore Fort</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #1d2671, #c33764);
            font-family: Arial, Helvetica, sans-serif;
        }

        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.15);
            padding: 25px;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
        }

        h1 {
            color: #ffffff;
            margin-bottom: 20px;
            letter-spacing: 2px;
        }

        img {
            width: 450px;
            max-width: 100%;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>VELLORE FORT</h1>
        <img src="vellore_fort.jpg" alt="Vellore Fort">
    </div>
</body>
</html>

~~~


## OUTPUT
<img width="1919" height="1079" alt="Screenshot 2025-12-13 112412" src="https://github.com/user-attachments/assets/ea7f7fdc-55c9-4ed2-98e4-eb0b423516a6" />

<img width="1919" height="1079" alt="Screenshot 2025-12-13 112428" src="https://github.com/user-attachments/assets/3959ab48-6da3-4a3e-b0cf-f4401659fa38" />

<img width="1919" height="1079" alt="Screenshot 2025-12-13 112441" src="https://github.com/user-attachments/assets/6ad8fab0-8c7e-48b6-8c3b-bc689afac8f2" />

<img width="1919" height="1079" alt="Screenshot 2025-12-13 112454" src="https://github.com/user-attachments/assets/75ec3f62-f260-43ae-9595-08676e7795ce" />




## RESULT
The program for implementing image maps using HTML is executed successfully.
