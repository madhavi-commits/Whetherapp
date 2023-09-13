<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App - InCoder</title>
    <link rel="stylesheet" href="main.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>

<body>
    <div class="mainContainer">
        <div class="searchInput">
            <input type="text" placeholder="Enter City Name" id="searchInput" value="New York"/>
            <button id="searchButton"><i class="fa-solid fa-magnifying-glass"></i></button>
        </div>
        <div class="weatherDetails">
            <div class="weatherIcon">
                <img src="Images/sun.png" alt="Clouds" id="weatherIcon">
            </div>
            <div class="cityDetails">
                <div class="weather" id="weather"></div>
                <div class="desc"></div>
            </div>
            <div class="windDetails">
                <div class="humidityBox">
                    <img src="Images/thermometer.png" alt="Humidity">
                    <div><p class="humidity"></p><span>Humidity</span></div>
                </div>
                <div class="windSpeed">
                    <img src="Images/wind.png" alt="Wind Speed">
                    <div><p id="windSpeed"></p><span>Wind Speed</span></div>
                </div>
            </div>
        </div>
    </div>

    <script src="script.js"></script>
</body>

</html>
