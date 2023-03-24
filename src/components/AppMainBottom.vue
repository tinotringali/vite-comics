<script>

export default{
    name:'AppMainBottom',
    data(){
        return{
            buyComics:[
                {
                image:'img/buy-comics-digital-comics.png',
                name:'DIGITAL COMICS'
                },
                {
                image:'img/buy-comics-merchandise.png',
                name:'DC MERCHANDISE'
                },      
                {
                image:'img/buy-comics-subscriptions.png',
                name:'SUBSCRIPTION '
                },   
                {
                image:'img/buy-comics-shop-locator.png',
                name:'COMIC SHOP LOCATOR '
                },   
                {
                image:'img/buy-dc-power-visa.svg',
                name:'DC POWER VISA'
                },   
            ]
        }
    }
}

</script>

<template>
    <main>
    <div class="icon-main">
        <div v-for="image in buyComics" class="buy">
            <img :src="image.image" alt="card">
            <h6>{{ image.name }}</h6>
        </div>
    </div>  
</main>
</template>

<style lang="scss" scoped>

main{
 background-color: #0282f9;
}

.icon-main{
    display: flex;
    justify-content: center;
}
.buy{
    display: flex;
    align-items: center;
    padding: 30px 35px;
}
img{
    width: 40px;
}

h6{
    color: white;
    margin-left: 10px;
}
</style>