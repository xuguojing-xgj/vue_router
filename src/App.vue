<template>
    <div>
        <h1>Vue Router</h1>
        <div>
            <router-link to="/">Login</router-link>
        </div>
        <div>
            <router-link to="/reg">Reg</router-link>
        </div>
        <hr>
        <!-- 导入注册完成之后 使用 router-view 路由出口 路由匹配到的组件将渲染到这里 -->
        <router-view></router-view>
    </div>
</template>
    
<script setup lang='ts'>

</script>
    
<style>

</style>