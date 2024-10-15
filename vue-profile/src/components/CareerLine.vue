<template>
  <v-card> 
    <v-card-title  class="text-left" > JOURNEY</v-card-title>
    <v-timeline align="start" reverse>
      <v-timeline-item
        v-for="(year, i) in years"
        :key="i"
        :dot-color="year.color"
        size="medium"
      >
        <template v-slot:opposite>
          <div
            :class="`pt-1 headline font-weight-bold text-${year.color}`"
            v-text="year.year"
          ></div>
        </template>
        <div>
          <!-- <h2 :class="`mt-n1 headline font-weight-light mb-4 text-${year.color}`">
            Lorem ipsum
          </h2> -->
          <div>
            {{year.experince}}
          </div>
        </div>
      </v-timeline-item>
    </v-timeline>
  </v-card>
  </template>
  <script>
    export default {
      data: () => ({
        years: [
          {
            color: 'cyan',
            year: '2005',
            experince:"CAD Engineer"
          },
          {
            color: 'green',
            year: '2014',
            experince:"CAD Engineer"
          },
          {
            color: 'pink',
            year: '2018',
            experince:"CAD Engineer"
          },
          {
            color: 'amber',
            year: '2021',
            experince:"CAD Engineer"
          }
        ],
      }),
    }
  </script>
  <style scoped>
  
.capitalize {
  text-transform: capitalize;
}
  </style>