
<template>
    <div class="my-2">
        <a class="card row">
          <div class="grid grid-cols-2 block justify-center	">
            <div class="cols-span-1">
               <p>2019 - 2020</p> 
            </div>
            <div class="cols-span-1">
              <p>Bac S - lycée françois mansart</p>
            </div>
          </div>
        </a>

    </div>
    <div class="my-2">
        <a class="card row ">
          <div class="grid grid-cols-2 flex justify-center">
            <div class="cols-span-1">
               <p>2021 - 2022</p> 
            </div>
            <div class="cols-span-1">
              <p>Développeur web et web mobil niveau v - Simplon Roanne</p>
            </div>
          </div>
        </a>

    </div>
  </template>
  
  <style scoped>
.column{
  justify-content: center;
}

p{
  color: rgb(0, 0, 0);
  font-family: Arial, Helvetica, sans-serif;
}
@media (min-width: 360px) { 

  svg{
    width: 100%;
    height: 40px;
    object-fit: cover;
  }
}

  </style>

<script>
export default {
    name: 'CardSkill',
}
</script>
