<template>
    <div >
        <div class="box">
            <img src="../assets/scott-estrada-developer.jpg" alt="">
            <p id="testo">Guarda come sono felice</p>
        </div>
            
            
        
    </div>
    
</template>

<script>

    export default{
        name: "AppHero",

    }
</script>

<style scoped>

.box {
  position: relative;   
}

#testo{
  position: absolute;
  z-index: 1;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: black;
}

</style>