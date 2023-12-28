<script>
import PropertiesFilters from "@/components/PropertiesFilters.vue";
import PropertiesListing from "@/components/PropertiesListing.vue";

export default {
  components: {
    PropertiesFilters,
    PropertiesListing,

  },
};
</script>

<template>
  <main>
    <PropertiesFilters />
    <PropertiesListing />
    
  </main>
</template>
