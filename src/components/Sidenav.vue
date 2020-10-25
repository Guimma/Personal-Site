<template>
  <div class="grid">
    <div class="sidenav">
      <h2 class="name">Lucas Campregher</h2>
      <div class="profile-pic">
        <img src="../assets/images/lucas.jpg" alt="Lucas Campregher">
      </div>
    </div>
    <div class="container">
      <h1>CARIOCA BOIZAO MU</h1>
    </div>
  </div>  
</template>

<script>
export default {
  name: 'Sidenav',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@media only screen and (min-width: 992px){
  .grid {
    width: 100vw;
    height: 100vh;
    display: grid;
    grid-template-columns: 300px auto; 
  }

  .sidenav {
    grid-column: 1;
    height: 100%;
    background-color: #5AA9E6;
    padding: 24px 16px 24px 16px;
  }

  .container {
    grid-column: 2;
  }

  .name {
    color: #f8f9fa;
  }

  .profile-pic {
    width: 180px;
    margin: 24px auto 0 auto;
  }

  .profile-pic img {
    width: 100%;
    height: auto;
    border-radius: 50%;
  }
}
</style>
