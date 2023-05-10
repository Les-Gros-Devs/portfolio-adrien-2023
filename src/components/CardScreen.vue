
<template>
    <div class="card-container my-2 w-full">
      <div class="w-1/2">
        <a class="card-50 row h-card-body screen-1"  target="_blank">
          <div class="content">
            <div class="">
            </div>
          </div>
        </a>
      </div>
      <div class="w-1/2">
        <div class="grid grid-rows-2 h-card-body w-full">
          <div class="mb-1">
            <a class="card-50 row mb-2 screen-2">
            </a>
            <a class="card-50 row m-0 screen-3">
            </a>
          </div>
        </div>
      </div>
    </div>
  </template>
  

  <style scoped>
.screen-1{
  background-image: url("../assets/img/rap_site_model.png");
  background-size: cover;
  background-position: left;
  background-repeat: no-repeat;

}
.screen-2{
  background-image: url("../assets/img/drumpad.png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;

}
.screen-3{
  background-image: url("../assets/img/instaclone.png");
  background-size: cover;
  background-position: 25%;
  background-repeat: no-repeat;
  
}
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
  height: 520px;
}

@media (min-width: 360px) { 


}

  </style>

<script>
export default {
    name: 'CardScreen',
}
</script>
