<template>
     <div id="main">
        <Header title="时代影院"/>
        <TabBar />
    </div>
</template>

<script>

import Header from '@/components/Header';
import TabBar from '@/components/TabBar';

export default {
    name : 'Cinema',
     components : {
        Header,
        TabBar
    }
}
</script>

<style>

</style>