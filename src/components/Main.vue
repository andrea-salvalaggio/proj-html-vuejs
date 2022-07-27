<template>
    <div>
      <ServicesElement/>
      <MissionsElement/>
      <ProjectsElement/>
    </div>
</template>

<script>
import ServicesElement from './Section/ServicesElement.vue';
import MissionsElement from './Section/MissionsElement.vue';
import ProjectsElement from './Section/ProjectsElement.vue';

export default {

  components: {
        ServicesElement,
        MissionsElement,
        ProjectsElement,
    },

}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

</style>