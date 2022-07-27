<template>
    <div>
      <ServicesElement/>
      <MissionsElement/>
      <ProjectsElement/>
      <DataElement/>
    </div>
</template>

<script>
import ServicesElement from './Section/ServicesElement.vue';
import MissionsElement from './Section/MissionsElement.vue';
import ProjectsElement from './Section/ProjectsElement.vue';
import DataElement from './Section/DataElement.vue';

export default {

  components: {
        ServicesElement,
        MissionsElement,
        ProjectsElement,
        DataElement,
    },

}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

</style>