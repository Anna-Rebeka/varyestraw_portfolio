<template>
    <header>
        <div class="flex items-center m-auto max-w-max p-8 mt-3">
            <router-link  to="/"><h1 class="text-4xl" style="letter-spacing: 0.25em;">VARYESTRAW</h1></router-link> 
        </div>

        <div id="nav">
            <router-link  to="/">HOME </router-link> 
            <router-link  to="/illustrations">ILLUSTRATIONS </router-link> 
            <router-link  to="/character-design">CHARACTER DESIGN </router-link> 
            <router-link  to="/art-series">ART SERIES </router-link> 
            <router-link  to="/sketches">SKETCHES </router-link> 
            <router-link  to="/commission">COMMISSION </router-link> 
            <router-link  to="/about">ABOUT</router-link>
        </div>
    </header>
    
  <router-view/>
</template>

<style>
#app {
  font-family: Century Gothic, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 20px;
  margin-bottom: 20px;
}

#nav a {
  color: #2c3e50;
   letter-spacing: 1px;
   margin: 12px;
}

#nav a:hover {
  color: #b4b4b4;
}

#nav a.router-link-exact-active {
  color: #b4b4b4;
}
</style>
