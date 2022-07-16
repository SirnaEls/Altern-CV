<template>
  <div class="navvbar">
    <div>
      <img src="/src/assets/LogoAlternCV.png" alt="" />
    </div>
    <div class="navigation">
      <ul id="navbar">
        <li> Le CV</li>
        <li> À propos</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
* {
  background: black;
}

img {
  width: 200px;
  height: auto;
  margin: 20px;
}

.navvbar{
  display: flex;
  justify-content: space-between;
  margin-right: 140px;
  margin-top: 20px;
  box-sizing: border-box;
}

.navigation{
 
  font-size: 20px;
  color:white;

}

#navbar{
  list-style: none;
  display: flex;
  gap: 40px;
  font-family:Verdana, Geneva, Tahoma, sans-serif;
 
}
</style>
