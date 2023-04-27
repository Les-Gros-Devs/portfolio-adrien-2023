<template>
  <div class="card row">
    <div class="column img-column-pp">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTH_lx0q2AyF1JGCa3cyDHI_DdHvO-XhmvI1Q&usqp=CAU" >
    </div>
    <div class="column">
      <div>
        <h3>Thomas Adrien</h3>
      </div>
      <div>
        <p>Available for freelance projects</p>
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
}
@media (min-width: 360px) { 
  img{
    width: 100%;
    height: 40px;
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
