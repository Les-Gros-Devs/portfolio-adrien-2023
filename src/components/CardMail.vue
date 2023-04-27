
<template>
    <div class="my-2">
        <a class="card row" href="mailto:adrienthomas54@icloud.com">
          <div class="column">
             <!-- <p>📧</p>  -->
             <svg fill="none" viewBox="0 0 24 24" stroke="currentColor" width="24" height="24" color="rgb(161, 161, 170)"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
          </div>
          <div class="column">
            <p>adrienthomas54@icloud.com</p>
          </div>
        </a>

    </div>
  </template>
  
  <style scoped>
.column{
  justify-content: center;

}
svg{
  width: 40px;
  height: 100%;
  object-fit: cover;
}
p{
  color: rgb(161, 161, 170);
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
    name: 'CardMail',
}
</script>
