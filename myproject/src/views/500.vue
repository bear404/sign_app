<template>
<div class="button-container">
    <p class="page-container">500 page not found</p>
    <router-link to="../table">
        <el-button round class="button-container">返回</el-button>
    </router-link>
</div>
</template>


<style lang="scss" scoped>
    .page-container {
        font-size: 60px;
        text-align: center;
        color: rgb(192, 204, 218);
    }
    .button-container {
              font-size: 30px;
              text-align: center;
              /*color: rgb(192, 204, 218);*/
          }
</style>
<!--<script>-->
    <!--methods:{-->
        <!--gotolink()-->
        <!--{-->
            <!--this.$router.push({path: '/main'})-->
        <!--}-->
    <!--}-->
<!--</script>-->