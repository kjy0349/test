<template>
  <div class="hello">
      <router-link to="About"><el-button class="button1"><span style="color:darkseagreen;font-size:35pt;"><I>Alpha Mining</I></span><br><br><br>
    <span style="color:darkseagreen;font-size:12pt">Alpha란 무엇인가?<br><br></span>
      <span style="color:darkseagreen;font-size:12pt">AlphaMining Service를 당장 활용해보세요!<br><br></span>
      </el-button></router-link>
      <router-link to="DataPage">
          <el-button class="button2"><span style="color:darkseagreen;font-size:35pt"><I>Minning Tool</I></span><br><br><br>
      <span style="color:darkseagreen;font-size:12pt">Alpha Mining 서비스<br><br></span>
      <span style="color:darkseagreen;font-size:12pt">차트를 활용한 사용자 인터페이스<br><br></span>
    </el-button></router-link>
      <router-link to="SidePage">
          <el-button class="button3"><span style="color:darkseagreen;font-size:35pt"><I>Contact</I></span><br><br><br>
      <span style="color:darkseagreen;font-size:12pt">어려움이 있으시다면<br><br></span>
      <span style="color:darkseagreen;font-size:12pt">저희 Alpha Mining의 최고의 투자자들과<br><br></span>
      <span style="color:darkseagreen;font-size:12pt">Ticket과 Chat을 통해 소통하십시오.</span></el-button></router-link><br><br><br><br>

  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class HelloWorld extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .button2{
    width:400px;
    height:300px;
    margin-right:50px;
    /*background-image: url("//i.imgur.top/c/A/308998ber3prealcatter.jpg");*/
    background-size: cover;
  }
  .button1{
    width:400px;
    height:300px;
    margin-right:50px;
    /*background-image: url("//i.imgur.top/c/A/373022oa5kcstock.jpg");*/
    background-size: cover;
  }
  .button3{
    width:400px;
    height:300px;
      margin-right:50px;
      /*background-image: url("//i.imgur.top/c/A/359144487ifready.jpg");*/
      background-size: cover;
  }
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
