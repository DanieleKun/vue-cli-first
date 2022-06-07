<template>
    <div>
        <div id="jumbo">
            <img src="../assets/Flat Minimalist Space 04.png" alt="">
            <div id="jumbo-text">
                <h2>Fatti rapire da Vue CLI!!</h2>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'JumboTron'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#jumbo {
    position: relative;
}

#jumbo img {
    width: 100%;
    height: 550px;
    object-fit: cover;
}

#jumbo-text{
    position: absolute;
    top: 100px;
    left: 200px;
}

h2 {
    font-size: 40px;
    color: rgb(232, 232, 232)
}
</style>