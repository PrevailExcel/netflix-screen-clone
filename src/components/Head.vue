<script setup>

</script>
<template>
    <div class="head-nav">
        <img class="img-fluid" src="/netlogo.png">

        <div class="my-auto bloc-icon d-flex justify-content-center">
                <i class="fa fa-search"></i>

                <i class="ms-4 p-3 fa profile bg-primary rounded"></i>
        </div>
    </div>
</template>
<style scoped>
.head-nav {
    background: #0000009a;
    position: fixed;
    top: 0;
    height: 65px;
    width: 100%;
    padding: 10px 6px;
    display: flex;
    justify-content: space-between;
}

.bloc-icon {
    color: white;
    font-size: 26px;
}

.bloc-icon small {
    font-size: 11px;
}

.active {
    color: white;
    padding: 10px;
}
.profile{
    font-size: 255px !important;
}
</style>