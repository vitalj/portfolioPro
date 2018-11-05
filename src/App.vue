<template>
<div>
      <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css">
<link href="https://fonts.googleapis.com/css?family=Nunito|PT+Sans" rel="stylesheet">

<div class="skewed-bg">

</div>

        <div class="navbar">
      <ul>
        <li>
          <router-link to="/">Accueil</router-link>
        </li>
        <li>
          <router-link to="/resume">Mon CV</router-link>
        </li>
        <li>
          <router-link to="/projects">Mes projets</router-link>
        </li>
      </ul>
    </div>
    <router-view />

  </div>
</template>
<style>

.skewed-bg {
  background: #00B285;
  -webkit-transform: skew(0deg, -5deg);
  transform: skew(0deg, -8deg);
  padding: 100px 0;
  margin-top: -100px;
}

h1 {
font-family: 'Nunito', sans-serif;
Font-Size: 2.5rem;
}

h2 {
font-family: 'Nunito', sans-serif;
  Font-Size: 2rem;
}

h3 {
font-family: 'Nunito', sans-serif;
}

body {
  margin-top:0;
  margin-bottom: 0;
  background: #222;
  text-align: center;
  Font-Size: 15px; 
  position: relative;
  color: white;
}

.navbar {
  background: black;
  height: 5vh;
  position: fixed;
  overflow: hidden;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1;
  -webkit-transition: .13s all;
  transition: .13s all;
    box-sizing: border-box;
  margin: 0;
  padding: 0;
font-family: 'Nunito', sans-serif;

}

.navbar ul {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 95vw;
  box-sizing: border-box;
  overflow: hidden;
  margin: 0;
  padding: 0;
}

.navbar ul li {
  list-style: none;
}


.navbar li:first-child {
  margin-right: auto;
  font-weight: bold;
}

.navbar a {
  text-decoration: none;
    font-size: 1.2rem;
  padding: 12px;
   color: white;
   -webkit-transition: .3s all;
  transition: .3s all;

}

.navbar a:hover {
  color: grey;
}

</style>
<script>

</script>