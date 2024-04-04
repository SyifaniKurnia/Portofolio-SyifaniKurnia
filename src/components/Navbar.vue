<template>
  <div>
    <nav class="navbar" x-data>
      <a href="#" class="navbar-logo"><span>Syifani</span></a>

      <div class="navbar-nav">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#background">Background</a>
        <a href="#project">Projects</a>
        <a href="#experience">Experience</a>
      </div>
    </nav>
  </div>
</template>

<style scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.4rem 7%;
  background-color: rgba(155, 72, 20, 0.9);
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 9999;
}

.navbar .navbar-logo {
  font-size: 2rem;
  font-weight: bold;
  color: #fff;
}

.navbar .navbar-logo span {
  color: #fff;
}

.navbar .navbar-nav {
  display: flex;
  justify-content: flex-end;
}

.navbar .navbar-nav a {
  color: #fff;
  display: inline-block;
  font-size: 1.3rem;
  margin: 0 1rem;
}
</style>
