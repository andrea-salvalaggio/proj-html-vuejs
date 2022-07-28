<template>
    <div class="tertiary-bg padding-t padding-b">

        <!-- Components of images partners -->
        <CardPartner/>
        
    </div>
</template>

<script>
import CardPartner from '../Card/CardPartner.vue';

export default {

    components: {
        CardPartner,
    },

}
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";

    .tertiary-bg{
        background-color: $tertiaryColorBg;
        position: relative;
        bottom: 150px;
        z-index: -1;
    }

    .padding-t{
        padding-top: 300px;
    }

    .padding-b{
        padding-bottom: 150px;
    }

</style>