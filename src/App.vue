<template>
<div>
    <Navigation></Navigation>
    <router-view></router-view>
</div>
</template>


<script>

import Navigation from "./pages/Navigation.vue"

export default {
    components : {
        Navigation, 
    }
}

</script>

<style scoped>
div{
    display: flex;
}
</style>