<template>
    <div class="demo">
        <h2>学生姓名 {{ name }}</h2>
        <h2>学校性别 {{ age }}</h2>
    </div>
</template>

<script>
export default {
    name: "Student",
    data() {
        return {
            name: "张三",
            age: 19,
        };
    },
};
</script>

<style>
.demo {
    background-color: yellow;
}
</style>
