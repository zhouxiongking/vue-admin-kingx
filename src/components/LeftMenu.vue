<template>
    <div>
        <el-row class="tac">
            <el-col :span="24">
                <el-menu
                    default-active="2"
                    router
                    class="el-menu-vertical-demo">
                    <el-submenu index="1">
                        <template slot="title">
                            <i class="el-icon-location"></i>
                            <span>导航一</span>
                        </template>
                        <el-menu-item-group>
                            <el-menu-item index="/component1">选项1</el-menu-item>
                            <el-menu-item index="1-2">选项2</el-menu-item>
                            <el-menu-item index="1-1">选项3</el-menu-item>
                            <el-menu-item index="1-2">选项4</el-menu-item>
                        </el-menu-item-group>
                    </el-submenu>
                    <el-menu-item index="/component2">
                        <i class="el-icon-menu"></i>
                        <span slot="title">导航二</span>
                    </el-menu-item>
                    <el-menu-item index="3">
                        <i class="el-icon-document"></i>
                        <span slot="title">导航三</span>
                    </el-menu-item>
                    <el-menu-item index="4">
                        <i class="el-icon-setting"></i>
                        <span slot="title">导航四</span>
                    </el-menu-item>
                    <el-menu-item index="5">
                        <i class="el-icon-menu"></i>
                        <span slot="title">导航五</span>
                    </el-menu-item>
                    <el-menu-item index="6">
                        <i class="el-icon-document"></i>
                        <span slot="title">导航六</span>
                    </el-menu-item>
                    <el-menu-item index="7">
                        <i class="el-icon-setting"></i>
                        <span slot="title">导航七</span>
                    </el-menu-item>
                    <el-menu-item index="8">
                        <i class="el-icon-document"></i>
                        <span slot="title">导航八</span>
                    </el-menu-item>
                    <el-menu-item index="9">
                        <i class="el-icon-setting"></i>
                        <span slot="title">导航九</span>
                    </el-menu-item>
                    <el-menu-item index="10">
                        <i class="el-icon-menu"></i>
                        <span slot="title">导航十</span>
                    </el-menu-item>
                    <el-menu-item index="11">
                        <i class="el-icon-document"></i>
                        <span slot="title">导航十一</span>
                    </el-menu-item>
                    <el-menu-item index="12">
                        <i class="el-icon-setting"></i>
                        <span slot="title">导航十二</span>
                    </el-menu-item>
                </el-menu>
            </el-col>
        </el-row>
    </div>

</template>

<script>

    export default {
        name: "left-menu"
    }
</script>

<style scoped>

</style>
