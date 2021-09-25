<template>
  <div class="pare bg-danger p-3">
    <h3>{{ msg }}</h3>
    <Fill msg="Soc el fill"></Fill>
  </div>
</template>

<script>
import Fill from '../../src/components/Fill.vue'

export default {
    name: 'Pare',
    props: {
        msg: String
    },
    components: {
        Fill
    }
}
</script> 