<template>
  <v-card
    title="TECHNICAL SKILLS"
class="text-left"
  >
      <template v-slot:text>
      <v-text-field
        v-model="search"
        label="Search"
        prepend-inner-icon="mdi-magnify"
        variant="outlined"
        hide-details
        single-line
      ></v-text-field>
    </template>
  <v-data-table
    :headers="headers"
    :items="items"
    item-key="skills"
    items-per-page="-1"
    :search="search"
  ><template v-slot:item.name="{ item }">
      <td class="first-column">{{ item.name }}</td>
    </template></v-data-table>
  </v-card>
</template>

<script setup>
  import { ref } from 'vue'

  const search = ref('')
  </script>
<script>
export default {
  data() {
    return {
      search: '',
      headers: [
        { text: 'Category', value: 'category' },
        { text: 'Skills', value: 'skills' }
      ],
      items: [
    {
      "category": "Architectural patterns",
      "skills": "MVC MVVM MACH"
    },
    {
      "category": "UI Development",
      "skills": 
        "TypeScript, JavaScript, HTML5, CSS3, Angular(v2,4,6,8,12,16), React, VueJs(v2.4,2.7,3), Svelte, Remix, Nuxt, Next.js, Sass, Less, Tailwind, Bootstrap, PHP (v3,4,5), JSP, ASP, Tcl/Tk, Qt"
      
    },
    {
      "category": "UX Prototyping",
      "skills":"Sketch, Figma, Adobe XD, LucidDraw"
    },
    {
      "category": "Backend development",
      "skills":"Python(v2.4,v2.7,v3), Node(v12-22), Deno, Golang, Rust"
    },
    {
      "category": "System Integrations",
      "skills":"REST, RPC, gRPC, SOAP, IPC, Electronic Data Interchange(EDI)"
    },
    {
      "category": "AuthTech",
      "skills":"OpenID Connect, OAuth2, FIDO, PassKeys"
    },
    {
      "category": "Build tools and code packaging",
      "skills":"Rollup, Webpack, Make, Grunt, Gulp, Snaps, deb, rpms"
    },
    {
      "category": "Infrastructure as Code",
      "skills": 
        "Terraform, Puppet, Chef, Jenkins, GitHub Actions, Azure Pipelines, CircleCI, CloudFormation"
      
    },
    {
      "category": "Mobile app development",
      "skills":"Ionic, Cordova, Capacitor, Flutter, React Native, Phonegap"
    },
    {
      "category": "Cloud platforms",
      "skills":"AWS, Azure, GCP, Digital Ocean"
    },
    {
      "category": "Cluster management",
      "skills":"Kubernetes, Docker Swarm, Flowtracer, LSF"
    },
    {
      "category": "Project Management",
      "skills":"Jira, Rally, Azure Boards, Asana"
    },
    {
      "category": "Data Management",
      "skills":"MySQL, PostgreSQL, SQLite, Apache Cassandra"
    },
    {
      "category": "Big Data",
      "skills": 
        "Apache Hadoop, Spark, Flume, Datalake, data mesh, Elastic Search, PowerBI, Tableau, Sumologic"
      
    },
    {
      "category": "Version Control Systems",
      "skills": 
        "Git (GitHub Enterprise, Azure Repos, Bitbucket, Gitlab), Perforce, DesignSync"
      
    },
    {
      "category": "Generative AI",
      "skills":"OpenAI, Claude, Pi, Gemini"
    },
    {
      "category": "IoT systems",
      "skills": 
        "AWS IoT, Google IoT, Azure IoT, BLE, MQTT, LoRaWAN, Zigbee, Kafka"
      
    },
    {
      "category": "Natural Language Processing",
      "skills":"Azure AI Language,Azure AI Speech, Azure AI Translator"
    }
  ]
}

  }
};
</script>

<style scoped>
.first-column {
  /* Add your custom styles here */
  background-color: #f0f0f0;
  font-weight: bold;
}
.v-card-title {
  font-weight: bold;
}
</style>
