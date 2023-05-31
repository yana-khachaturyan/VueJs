<template>
<NavbarSection></NavbarSection>
<div class="app">

<router-view> </router-view>
 </div>
</template>

<script> 
import NavbarSection from '@/components/UI/NavbarSection'
export default {
    components: {
        NavbarSection
    }
}

</script>

<style> 
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
.app{
    padding: 20px
}
</style> 