<template>
  <!-- <div class="card row">
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
  </div> -->
  <!-- part form contacte lgd -->
  <section>
  <form class="contact-form row">
      <div class="form-field col x-50">
        <label class="label" for="name" v-translate="'Surname'" id="Surname">Votre Nom</label>
         <input id="name" class="input-text js-input" type="text" required>
      </div>
      <div class="form-field col x-50">
        <label class="label" for="name" v-translate="'Name'" id="Name">Votre Prenom</label>
         <input id="name" class="input-text js-input" type="text" required>
      </div>
      <div class="form-field col x-50">
        <label class="label" for="email" v-translate="'E-mail'" id="E-mail">Votre E-mail</label>
         <input id="email" class="input-text js-input" type="email" required>
      </div>
      <div class="form-field col x-100">
        <label class="label" for="message" v-translate="'Message'" id="Message">Votre message</label>
         <input id="message" class="input-text js-input" type="text" required>
      </div>
      <div class="form-field col x-100 align-center">
         <input class="submit-btn" type="submit" value="Submit">
      </div>
   </form>
  </section>


  
</template>

<style scoped>
/* part form contacte lgd */
.input-text {
      display: block;
      width: 100%;
      height: 36px;
      border-width: 0 0 2px 0;
      border-color: #000;
      font-family: Lusitana, serif;
      font-size: 18px;
      line-height: 26px;
      font-weight: 400;
   }
label{
  border-radius: 10%;
}

section{
  width: 100%;
}














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