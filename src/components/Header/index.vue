<template>
    <header id="header">
        <h1>{{ title }}</h1>
    </header>
</template>

<script>
export default {
    name : 'Header',
    props:{
        title:{
            type:String,
            default:'时代电影'
        }
    }
}
</script>

<style scoped>
    #header{
       width: 100%;
       height: 50px;
       color: #fff;
       background: pink;
       border-bottom: 1px solid #d48181;position: relative;
    }

    #header h1{
        font-size: 25px;
        text-align: center;
        color: rgb(255, 0, 106);
        line-height: 50px;
        font-weight: normal;
    }

    #header i{
        position: absolute;
        left: 5px;
        top: 50%;
        margin-top: -13px;
        font-size: 26px;
    }
</style>
