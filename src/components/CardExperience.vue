
<template>
    <div class="card-container my-2 flex justify-start">
        <!-- <div class="column-part my-2"> -->
            <a class="card-50 row h-card-body"  target="_blank">
              <div class="content">
                <div class="">
                    <h3>FDI Partner</h3>
                  <p>Stage de deux moi a la fin de ma formation</p>

                </div>
              </div>
            </a>
        <!-- </div>
        <div  class="column-part my-2"> -->
            <a class="card-50 row h-card-body" target="_blank">
              <div class="">
                <h3>France Decor</h3>
                <p>Travaille en industrie</p>
              </div>
            </a>
        <!-- </div> -->
    </div>
    <div class="card-container my-2 w-full">
            <a class="card-50 row h-card-body"  target="_blank">
              <div class="content">
                <div class="">
                    <h3>Media 6</h3>
                  <p>Travaille en industrie</p>

                </div>
              </div>
            </a>
            <div class="grid grid-rows-2 h-card-body w-full">
                <a class="card-50 row">
                    Mon CV
                </a>
                <a class="card-50 row">

                </a>
            </div>
    </div>
  </template>
  

  <style scoped>
  .card-50{
    width: 100%;
}
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
.h-card-body{
  height: 210px;
}

@media (min-width: 360px) { 


}

  </style>

<script>
export default {
    name: 'CardExperience',
}
</script>
