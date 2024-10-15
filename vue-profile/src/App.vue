<script setup>
import CareerLine from './components/CareerLine.vue';
import RecentEmployments from './components/RecentEmployments.vue';
import Certifications from './components/Certifications.vue';
import TechnicalSkills from './components/TechnicalSkills.vue';
</script>


  <template>
    <RecentEmployments  />
    <Certifications  />
  <v-card>
    <v-tabs
      v-model="tab"
      align-tabs="center"
      color="deep-purple-accent-4"
    >
    <v-tab :value="1">Solution Architect</v-tab>
    <v-tab :value="2">DevOps Architect</v-tab>
      <v-tab :value="3">Technical Project Manager</v-tab>
      <v-tab :value="4">Product Owner</v-tab>
      <v-tab :value="5">Hands-on Developer</v-tab>
      <v-tab :value="6">CAD & Design Methodology Engineer</v-tab>
    </v-tabs>

    <v-tabs-window v-model="tab">
      <v-tabs-window-item
        v-for="n in 6"
        :key="n"
        :value="n"
      >
        <v-container fluid>
          <v-row>
            
              Hello {{ n }}
          </v-row>
        </v-container>
      </v-tabs-window-item>
    </v-tabs-window>
  </v-card>
  <CareerLine />
  <TechnicalSkills />
</template>
<script>
  export default {
    data: () => ({
      tab: null,
    }),
  }
</script>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
