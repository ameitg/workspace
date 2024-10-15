<template>
    <v-expansion-panels variant="accordion" v-model="activePanel">
      <v-expansion-panel class="text-left" >
      <v-expansion-panel-title class="h3">
        CERTIFICATIONS
    </v-expansion-panel-title>
    <v-expansion-panel-text>
      <UL>
    <LI>
        Microsoft Certified: Azure AI Fundamentals (AI-900)
    </LI>
</UL>
      </v-expansion-panel-text>
    </v-expansion-panel>
    </v-expansion-panels>

</template>
<script>
export default {
  data() {
    return {
      activePanel: [0], // Keep the first panel open by default
    };
  },
};
</script>
<style scoped>
  .h3 {
    text-transform: capitalize;
    font-weight:bold;
    font-size:larger
  }
  </style>