<script setup>
</script>

<template>
  <!--<div>
        <a href="https://vitejs.dev/" target="_blank">
                <img src="/vite.svg" class="logo" alt="Vite logo" />
              </a>
              <a href="https://vuejs.org/" target="_blank">
                <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
              </a>
            </div>-->
  <div class="wrapper">
    <div class="leftContainer">
      <div class="left-column">
        <div class="left-column">
  <div class="logo">
    <img src="cuacane-logo.png" alt="Cuacane">
  </div>
  <ul class="menu">
    <li><a href="#" class="active"><img src="dashboard-logo.png" alt="Dashboard">Dashboard</a></li>
    <li><a href="#"><img src="map-logo.png" alt="Map">Map</a></li>
    <li><a href="#"><img src="heart-logo.png" alt="Saved Locations">Saved Locations</a></li>
    <li><a href="#"><img src="calendar-logo.png" alt="Calendar">Calendar</a></li>
    <li><a href="#"><img src="settings-logo.png" alt="Settings">Settings</a></li>
  </ul>
  <div class="logout">
    <img src="logout-logo.png" alt="Log Out">
    <a href="#">Log Out</a>
  </div>
</div>
</div>

    </div>
    <div class="middleContainer">
      <div class="window-section">
  <div class="window">
    <div class="text-container">
      <div class="row1">Wind</div>
      <div class="row2">Today wind speed</div>
      <div class="row3">12km/h</div>
    </div>
    <img src="image1.jpg" alt="Image 1" class="image">
  </div>
  <div class="window">
    <div class="text-container">
      <div class="row1">Rain Chanse</div>
      <div class="row2">Today rain chanse</div>
      <div class="row3">24%</div>
    </div>
    <img src="image2.jpg" alt="Image 2" class="image">
  </div>
  <div class="window">
    <div class="text-container">
      <div class="row1">Pressure</div>
      <div class="row2">Today Pressure</div>
      <div class="row3">720 hpa</div>
    </div>
    <img src="image3.jpg" alt="Image 3" class="image">
  </div>
  <div class="window">
    <div class="text-container">
      <div class="row1">UV Index</div>
      <div class="row2">Today UV Index</div>
      <div class="row3">2</div>
    </div>
    <img src="image4.jpg" alt="Image 4" class="image">
  </div>
</div>

    </div>
    <div class="rightContainer">
      PRAVÝ
    </div>
  </div>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap');


* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
  }
  
.prev {
  display: flex;
    gap: 20px;
    justify-content: space-between;
    padding: 0 20px;
}

.middleContainer {
  width: 60%;
  background-color: lightgray
}

.wrapper {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.rightContainer {
  background-color: lightgray;
  width: 25%;
}

.leftContainer {
  width: 15%;
  background-color: lightgray;
}

.left-column {
  height: 100vh;
  background-color: #f2f2f2;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
}

.logo img {
  width: 100px;
  height: 100px;
  margin: 20px 0;
}

.menu {
  list-style: none;
  padding: 20px 0;
  margin: 0;
}

.menu li {
  margin-bottom: 10px;
}

.menu a {
  display: flex;
  align-items: center;
  color: #333;
  text-decoration: none;
  padding: 10px;
  transition: background-color 0.3s ease;
}

.menu a:hover {
  background-color: #ccc;
}

.menu a.active {
  background-color: #ccc;
  font-weight: bold;
}

.menu img {
  width: 20px;
  height: 20px;
  margin-right: 10px;
}

.logout {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
}

.logout img {
  width: 20px;
  height: 20px;
  margin-right: 10px;
}

.logout a {
  color: #333;
  text-decoration: none;
}



.window-section {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  height: 400px;
  background-color: #f2f2f2;
  padding: 20px;
}

.window {
  width: 45%;
  height: 45%;
  background-color: white;
  border: 1px solid #ccc;
  box-shadow: 0 0 10px rgba(0,0,0,0.3);
  margin-bottom: 20px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}

.text-container {
  width: 50%;
  height: 50%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  padding: 20px;
}

.row1 {
  font-size: 20px;
}

.row2 {
  font-size: 16px;
}

.row3 {
  font-size: 20px;
}

.image {
  width: 45%;
  height: 50%;
  object-fit: cover;
}

</style>