
<template>
    <div class="card-container my-2 w-full">
      <div class="w-1/2">
        <a class="card-50 row h-card-body"  target="_blank">
          <div class="content">
            <div class="">
                <h3>screen 1</h3>

            </div>
          </div>
        </a>
      </div>
      <div class="w-1/2">
        <div class="grid grid-rows-2 h-card-body w-full">
            <a class="card-50 row mb-2 ">
                screen 2
            </a>
            <a class="card-50 row mt-2 ">
                screen 3
            </a>
        </div>
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
