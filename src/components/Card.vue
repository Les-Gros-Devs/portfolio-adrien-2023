<template>
  <div class="card row">
    <div class="column img-column-pp">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTH_lx0q2AyF1JGCa3cyDHI_DdHvO-XhmvI1Q&usqp=CAU" sizes="40px"  >
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
.column{
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 1rem;
}
.card{
  display: flex;
  justify-content: space-between;
  width: 100%;
  height: 100%;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  padding: 1rem;
}
.row{
  flex-direction: row;
  padding: 1rem;
}
img{
  width: 100%;
  height: 40px;
  object-fit: cover;
  border-radius: 50%;
}
.img-column-pp{
  justify-content: center;
}

h3 {
  font-size: 1.2rem;
  text-align: start;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
<script>
  export default {
    name: 'Card',
  }
</script>