<script setup>

</script>
<template>
    <div class="mobile-nav mt-5">
        <a href="#" class="bloc-icon ripple">
            <i class="fa fa-home text-center active"><br><small>Home</small></i>
        </a>
        <a href="#" class="bloc-icon ripple">
            <i class="fa fa-bell text-center position-relative"><br><small>Games</small>
                <small class="position-absolute top-0 start-100 translate-middle badge rounded-circle bg-danger px-1 fs-small">2<small class="visually-hidden">unread messages</small></small>
            </i>
        </a>
        <a href="#" class="bloc-icon ripple">
            <i class="fa fa-play text-center"><br><small class="fs-smaller">News </small></i>
        </a>
        <a href="#" class="bloc-icon ripple">
            <i class="fa fa-user text-center"><br><small>Scenes</small></i>
        </a>
        <a href="#" class="bloc-icon ripple">
            <i class="fa fa-download text-center"><br><small>Downloads</small></i>
        </a>
    </div>
</template>
<style scoped>
.mobile-nav {
    background: #000000;
    position: fixed;
    bottom: 0;
    height: 65px;
    width: 100%;
    display: flex;
    justify-content: space-between;
}

.bloc-icon {   
    color: #564d4d !important;
    font-size: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.bloc-icon small {
    font-size: 11px;
}

.active {
    color: white;
    padding: 10px;
}
.sbadge{
    font-size: 7px;
}
</style>