<template>
    <div>
      <ServicesElement/>
      <MissionsElement/>
      <ProjectsElement/>
      <DataElement/>
      <ChatElement/>
      <QuoteElement/>
      <BlogElement/>
    </div>
</template>

<script>
import ServicesElement from './Section/ServicesElement.vue';
import MissionsElement from './Section/MissionsElement.vue';
import ProjectsElement from './Section/ProjectsElement.vue';
import DataElement from './Section/DataElement.vue';
import ChatElement from './Section/ChatElement.vue';
import QuoteElement from './Section/QuoteElement.vue';
import BlogElement from './Section/BlogElement.vue';

export default {

  components: {
        ServicesElement,
        MissionsElement,
        ProjectsElement,
        DataElement,
        ChatElement,
        QuoteElement,
        BlogElement,
    },

}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

</style>