<template>
<div>
    <h3>Soc el Pare</h3>
    <fill></fill>

</div>
</template>

<script>
import Fill from "./Fill.vue"

export default {
 
  name: 'Pare',
  components: {
      Fill
  },
   props: {
    msg: String
  }
 
 
}

</script>

<style  scoped>
div {
    background: #4018af;
    color: rgb(235, 191, 45);
    padding: 10px;
    height: 80px;
    width: 120px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    vertical-align: middle;
    align-items: center;
    
}

</style>