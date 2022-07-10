<template>
    <div class="full-width center-content">
        <h1>home</h1>
        <router-link to="/about" type="primary">主要链</router-link>
        <el-link type="success">成功链接</el-link>
        <el-link type="warning">警告链接</el-link>
        <el-link type="danger">危险链接</el-link>
        <el-link type="info">信息链接</el-link>
        <el-table :data="[{ name: '1' }]" height="200">
            <el-table-column prop="name" label="名称"></el-table-column>
            <el-table-column prop="name" label="名称"></el-table-column>
            <el-table-column prop="name" label="名称"></el-table-column>
        </el-table>
    </div>
</template>

<script>
export default {};
</script>
