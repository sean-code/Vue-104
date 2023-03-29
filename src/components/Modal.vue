<template>
    <div class='backdrop'>
        <div class="model">
            <p>Modal Content</p>
        </div>
    </div>
</template>

<style scoped>
.modal{
    width: 480px;
    padding: 20px;
    margin: 100px auto;
    background: #fafafa;
    border-radius: 10px;
}

.backdrop{
    top: 0;
    position: fixed;
    background: rgba(0, 0, 0, 0.5);
    width: 100%;
    height: 100%;
}

</style>