<template>
    <div class='fill bg-secondary text-white p-3'>
        <h4>{{ msg }}</h4>
    </div>
</template>

<script>
export default {
    name: 'Fill',
    props: {
        msg: String
    }
}
</script> 