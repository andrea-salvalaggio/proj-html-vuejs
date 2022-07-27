<template>
    <div>
      <ServicesElement/>
      <MissionsElement/>
    </div>
</template>

<script>
import ServicesElement from './Section/ServicesElement.vue';
import MissionsElement from './Section/MissionsElement.vue';

export default {

  components: {
        ServicesElement,
        MissionsElement,
    },

}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

</style>