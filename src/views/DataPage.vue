<template>
    <el-main class="Mining">
        <br><br>
        <span style="color:darkseagreen;font-size:40pt">Alpha Mining Tool</span><br><br><br>
        <p>
            저희 회사가 자랑하는 "Alpha Mining Tool"을 이용해 여러분의 미래를 설계 해보십시오.
        </p><br><br><br>


    </el-main>

</template>

<script lang="ts">
    import { Component, Vue } from 'vue-property-decorator';

    @Component({
        components:{
            DataPage
        }
    })
    export default class DataPage extends Vue {}
</script>

<style scoped>
    .about{
        line-height: 30px;
    }
</style>