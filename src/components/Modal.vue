<template>
    <div class="backdrop">
        <div class="model">
            <h1>{{ header }}</h1>
            <p>{{ content }}</p>
            <p>{{ arr }}</p>
        </div>
    </div>
</template>

<script>
    export default{
        props:['header', 'content', 'arr']
    }
</script>

<style scoped>
.modal{
    width: 400px;
    padding: 20px;
    margin: 100px;
    background: white;
    border-radius: 10px;
}

.backdrop{
    top: 0;
    position: fixed;
    background: rgb(246, 249, 249);
    width: 40%;
    height: 30%;
}
.modal h1{
    color: #03cfb4;
    border: none;
    padding: 0;
}

</style>