<template>
    <el-container class="home">
        <el-main>
            <img class = "Home" alt="Alpha Mining logo" src="http://i.imgur.top/c/A/578156gkr60Alpha Mining.png">
            <HelloWorld />
        </el-main>
    </el-container>
</template>

<script lang="ts">
    import { Component, Vue } from 'vue-property-decorator';
    import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

    @Component({
        components: {
            HelloWorld,
            Home
        }
    })
    export default class Home extends Vue {}
</script>

<style scoped>
    .Home{
        width:calc(50%);
    }
</style>