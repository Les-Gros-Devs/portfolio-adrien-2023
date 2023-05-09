
<template>
    <div class="my-2">
        <a class="card row" href="mailto:adrienthomas54@icloud.com">
            <p>basée en france, rhone</p>
            <p>UTC : +1</p>
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
    name: 'CardFooter',
}
</script>
