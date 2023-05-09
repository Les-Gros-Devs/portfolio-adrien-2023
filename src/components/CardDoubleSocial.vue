
<template>
    <div class="card-container my-2">
        <!-- <div class="column-part my-2"> -->
            <a class="card-50 row" href="https://www.linkedin.com/in/adrien-thomas-08845b229/" target="_blank">
              <div class="w-full flex justify-between">
                <div class="flex items-end">
                  <h3>Linkedin</h3>
                </div>
                <div class="">
                  <img src="../assets/img/linkedin.png">
                </div>
              </div>
            </a>
        <!-- </div>
        <div  class="column-part my-2"> -->
            <a class="card-50 row" href="https://github.com/adriennnnn/" target="_blank">
              <div class="w-full flex justify-between">
                <div class="flex items-end">
                  <h3>GitHub</h3>
                </div>
                <div class="">
                  <img src="../assets/img/github.png">
                </div>
              </div>
            </a>
        <!-- </div> -->
    </div>
  </template>
  

  <style scoped>
.content{
  display: flex;
}
path{
  height: 25px;
  width: 25px;
  height: auto;
  object-fit: cover;
  object-position: top right;
}
a{
  height: 210px;
}
img{
  width: 40px;
  height: 40px;
}
/* .card-icon{
  height: auto;
  object-fit: cover;
  object-position: top right;
}
.card-body{
  padding: 10px;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  display: flex;
  justify-content: flex-end;
  align-items: flex-start;
  flex-wrap: nowrap;
  align-content: flex-start;
  flex-direction: column;
} */

@media (min-width: 360px) { 


}

  </style>

<script>
export default {
    name: 'CardDoubleSocial',
}
</script>
