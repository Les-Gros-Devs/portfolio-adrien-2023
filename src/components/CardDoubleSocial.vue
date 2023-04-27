
<template>
    <div class="card-container my-2">
        <!-- <div class="column-part my-2"> -->
            <a class="card-50 row" href="https://www.linkedin.com/in/adrien-thomas-08845b229/" target="_blank">
              <div class="content">
                <div class="card-icon">
                  <svg viewBox="0 0 512 512">
                    <path d="M186.4 142.4c0 19-15.3 34.5-34.2 34.5 -18.9 0-34.2-15.4-34.2-34.5 0-19 15.3-34.5 34.2-34.5C171.1 107.9 186.4 123.4 186.4 142.4zM181.4 201.3h-57.8V388.1h57.8V201.3zM273.8 201.3h-55.4V388.1h55.4c0 0 0-69.3 0-98 0-26.3 12.1-41.9 35.2-41.9 21.3 0 31.5 15 31.5 41.9 0 26.9 0 98 0 98h57.5c0 0 0-68.2 0-118.3 0-50-28.3-74.2-68-74.2 -39.6 0-56.3 30.9-56.3 30.9v-25.2H273.8z"/>
                  </svg>
                </div>
                <div class="card-body">
                  <h3>Linkedin</h3>

                </div>
              </div>
            </a>
        <!-- </div>
        <div  class="column-part my-2"> -->
            <a class="card-50 row" href="https://github.com/adriennnnn/" target="_blank">
              <div class="">
                <svg></svg>

                <h3>GitHub</h3>
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
.card-icon{
  height: auto;
  object-fit: cover;
  object-position: top right;
}
.card-body{
  /* padding: 10px;
  display: flex;
  flex-direction: column;
  justify-content: flex-end; */
  display: flex;
  justify-content: flex-end;
  align-items: flex-start;
  flex-wrap: nowrap;
  align-content: flex-start;
  flex-direction: column;
}
@media (min-width: 360px) { 


}

  </style>

<script>
export default {
    name: 'CardDoubleSocial',
}
</script>
