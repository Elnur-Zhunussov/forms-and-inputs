<template>
    <signup-form-vue/>
</template>

<script>
import SignupFormVue from './components/SignupForm.vue'

export default {
    components: {SignupFormVue},
}
</script>

<style>
#app {
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

body {
    margin: 0;
    background: #eee;
}
</style>