<template>
<div class="teams" id="team">
<h3 class="teams-text">Silverline Team</h3>
<a href="https://www.linkedin.com/in/bala-kumaran-87900121a/" target="_blank"><img src="@/assets/balasir.png" alt="" class="sindhumam"></a>
<a href="https://www.linkedin.com/in/bala-kumaran-87900121a/" target="_blank"><img src="@/assets/bala1.png" alt="" class="sindhumam2"></a>
<a href="https://www.linkedin.com/in/shancoo/" target="_blank"><img src="@/assets/shaansir.png" alt="" class="sindhumam"></a>
<a href="https://www.linkedin.com/in/shancoo/" target="_blank"><img src="@/assets/sha1.png" alt="" class="sindhumam2"></a>
<a href="" target="_blank"><img src="@/assets/sindhumam.png" alt="" class="sindhumam1"></a>
<a href="" target="_blank"><img src="@/assets/sindhu1.png" alt="" class="sindhumam2"></a>
<a href="https://www.linkedin.com/in/allan-dias-454b3517/" target="_blank"><img src="@/assets/alansir.png" alt="" class="sindhumam"></a>
<a href="https://www.linkedin.com/in/allan-dias-454b3517/" target="_blank"><img src="@/assets/ala1.png" alt="" class="sindhumam2"></a>
<a href="https://www.linkedin.com/in/maheshmohan10/" target="_blank"><img src="@/assets/maheshsir.png" alt="" class="sindhumam"></a>
<a href="https://www.linkedin.com/in/maheshmohan10/" target="_blank"><img src="@/assets/mah1.png" alt="" class="sindhumam2"></a>
</div><br>
    
</template>
<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({})
export default class Teams extends Vue {}
</script>
<style>
.sindhumam2{
    display: none;
}
.sindhumam{
   width: 180px;
height: 240.88px;
position: relative;
margin: 30px;
}
.sindhumam1{
    width: 180px;
height: 270.88px;
position: relative;
margin: 2%;
margin-top: 0px;
}
.teams{
    position: static;
    top: 2000px;
    margin-bottom: 100px;
    text-align: center;
    margin-top: -400px;
}.teams-text{
font-family:moderne;
font-style: normal;
font-weight: 800;
font-size: 26.7361px;
line-height: 40px;
text-transform: uppercase;

color: #FFFFFF;


}@media screen and (max-width: 840px){
    .sindhumam1{
        height:auto ;
        width: 30%;
        display: none;
    }.sindhumam{
        width: 33%;
        height:auto ;
        display: none;
    }.sindhumam2{
        display: inline-block;
        width: 33%;
        margin: 15px;
    }
}
</style>