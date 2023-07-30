<template>
    <!-- this is the hero section along with the navbar -->
    <div class="">
        <banner/>
        <featurein/>
    </div>
</template>
<script>
    import banner from "../components/banner.vue"
    import featurein from "../components/featurein.vue";
    export default{
        name:"home",
        components:{
            banner,
            featurein
        }
    }
</script>