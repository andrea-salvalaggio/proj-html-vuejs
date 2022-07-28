<template>
    <div>
      <ServicesElement/>
      <MissionsElement/>
      <ProjectsElement/>
      <DataElement/>
      <PriceElement/>
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
import PriceElement from './Section/PriceElement.vue';
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
        PriceElement,
        QuoteElement,
        BlogElement,
        AskElement,
        PartnersElement,
    },

}
</script>

<style>

</style>