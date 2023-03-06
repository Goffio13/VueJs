<template>
  <div id="app">
      <div class="container-fluid">
        <nav class="navbar navbar-expand-lg sticky-top navbar-dark bg-dark">
            <span class="navbar-brand">VIE-IE-ED</span>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item active">
                        <router-link to="/"> <a class="nav-link">Acceuil</a></router-link> 
                    </li>
                    <li class="nav-item">
                         <router-link to="/import"><a class="nav-link">Import</a></router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/export"> <a class="nav-link">Export</a></router-link>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
