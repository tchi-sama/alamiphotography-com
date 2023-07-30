<template>
    <!-- this is the hero section along with the navbar -->
    <div class="">
        <banner/>
        <featurein/>
        <showCase/>
        <ourApproach/>
    </div>
</template>
<script>
    import banner from "../components/banner.vue"
    import featurein from "../components/featurein.vue";
    import showCase from "../components/showCase.vue";
    import ourApproach from "../components/ourApproach.vue";
    export default{
        name:"home",
        components:{
            banner,
            featurein,
            showCase,
            ourApproach,
        }
    }
</script>