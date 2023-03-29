<template>
    <div class="backdrop">
        <div class="model">
            <h1>Modal Title</h1>
            <p>Modal Content</p>
        </div>
    </div>
</template>

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