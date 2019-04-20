<template>
    <div id="app">
        <div class="left-menu">
            <left-menu></left-menu>
        </div>
        <div class="right">
            <div class="header">
                <k-header></k-header>
            </div>
            <div class="main">
                <!-- 装载跳转后的路由内容  -->
                <router-view></router-view>
            </div>
        </div>
    </div>
</template>

<script>
    import 'element-ui/lib/theme-chalk/index.css';
    import LeftMenu from './components/LeftMenu';
    import KHeader from './components/KHeader';

    export default {
        name: 'App',
        components: {
            'left-menu': LeftMenu,
            'k-header': KHeader
        }
    }
</script>

<style>
    * {
        margin: 0;
        padding: 0;
    }

    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
    }

    .left-menu {
        position: fixed;
        top: 0;
        bottom: 0;
        left: 0;
        width: 210px;
        color: #fff;
    }

    .right {
        margin-left: 210px;
    }
    .header {
        line-height: 50px;
        border-bottom: 1px solid #e3e3e3;
    }
</style>
