<template>
    <AppHeader/>
</template>


<script>
require('dotenv').config();

import AppHeader from "./components/Header"
export default {
    name:"App",
    components:{
        AppHeader
    }
    
}
</script>