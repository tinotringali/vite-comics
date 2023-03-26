<script>

import AppCards from './AppCards.vue';

export default{
    
    name:'AppMain',

    components:{
        AppCards
    }
}

</script>

<template>
<main>
    <section>
        <AppCards></AppCards>
    </section>
</main>
</template>

<style lang="scss" scoped>
main{
    width: 100vw;
    background-color: #1c1c1c;
}

h3{
color: white;
padding: 40px;
}

h6{
    color: white;
    margin-left: 20px;
}
</style>
