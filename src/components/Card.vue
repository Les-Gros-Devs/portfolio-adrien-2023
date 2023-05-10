<template>
  <div class="card row my-2">
    <div class="column img-column-pp">
      <img src="../assets/img/PP-adrien.jpg" >
    </div>
    <div class="column">
      <div>
        <h3>THOMAS Adrien</h3>
      </div>
      <div>
        <p>Disponible pour des projets en freelance</p>
      </div>
    </div>
  </div>
  <div>
    <p></p>
  </div>

</template>

<style scoped>

/* part av */


.row {
    flex-direction: row;
    padding: 1rem;
}

img {
    width: 40px;
    height: 40px;
    object-fit: cover;
    border-radius: 50%;
    max-width: none;
}
@media (min-width: 360px) { 
  img{
    width: 45px;
    height: 45px;
    object-fit: cover;
    border-radius: 50%;
  }
}

.img-column-pp {
    justify-content: center;
}

h3 {
    font-size: 1.2rem;
    text-align: start;
}

</style>
<script>
export default {
    name: 'Card',
}
</script>
