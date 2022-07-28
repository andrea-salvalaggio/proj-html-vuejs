<template>
    <div>
      <ServicesElement/>
      <MissionsElement/>
      <ProjectsElement/>
      <DataElement/>
      <ChatElement/>
      <QuoteElement/>
      <BlogElement/>
      <AskElement/>
      <PartnersElement/>
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
import AskElement from './Section/AskElement.vue';
import PartnersElement from './Section/PartnersElement.vue';

export default {

  components: {
        ServicesElement,
        MissionsElement,
        ProjectsElement,
        DataElement,
        ChatElement,
        QuoteElement,
        BlogElement,
        AskElement,
        PartnersElement,
    },

}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

</style>