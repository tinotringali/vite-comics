<script>

export default{
    name:'AppMain'
}

</script>

<template>
<main>
    <div class="content">
        <h3>Content goes here</h3>
    </div>
    <div class="icon-main">
        <div class="buy">
            <img src="img/buy-comics-digital-comics.png" alt="">
            <h6>DIGITAL COMICS</h6>
        </div>
    </div>  
</main>
</template>

<style lang="scss" scoped>
.content{
background-color: black;
}

h3{
color: white;
padding: 50px;
}

.icon-main{
 background-color: #0282f9;
}

.buy{
    display: flex;
    align-items: center;
    padding: 30px 0;
}
img{
    width: 50px;
}

h6{
    color: white;
    margin-left: 20px;
}
</style>
