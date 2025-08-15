<template>
    <div class="container p-3 d-flex justify-content-center">
        <div class="col-6 border" style="height: 100vh;">
            <i class="pi-bell" style="font-size: 2rem"></i>
        </div>
        <!-- <nav>
            <router-link to="/">Trang Chủ</router-link> |
            <router-link to="/about">Giới Thiệu</router-link>
        </nav> -->
        <!-- <router-view></router-view> -->
    </div>
</template>

<script>
export default {
    name: 'App',
};
</script>

<style scoped>
nav {
    margin-bottom: 20px;
}
nav a {
    margin-right: 10px;
    text-decoration: none;
    color: #42b983;
}
nav a.router-link-exact-active {
    font-weight: bold;
}
</style>