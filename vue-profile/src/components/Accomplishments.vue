<template>
<v-card class="text-left">
    <v-card-title class="capitalize">OTHER ACCOMPLISHMENTS</v-card-title>
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
         
         <div v-if="n==1">
            <ul>

<li>Architected and led a program with a team size of 16+ from inception to development, overseeing all stages of the migration of the monolith NetStar Platform to a MACH microservices-based platform, and collaborating closely with business and cross-functional project teams for Mercede-Benz USA at ATCS.</li>
<li>Architected and developed ETL process to migrate data from legacy on-prem monolith PostgreSQL to Amazon Aurora PostgreSQL for Mercede-Benz USA at ATCS.</li>
<li>Architected migration of Solr-based enterprise search to AWS OpenSearch based system for managing vehicle recall information for Mercede-Benz USA at ATCS.</li>
<li>Architected SaaS solutions for managing FreeRADIUS to manage WiFi networks.</li>
</ul>
        </div>
         <div v-if="n==2">
            Hello
        </div>
         <div v-if="n==3">
            <ul>
                
                        
                <li>Managed project scope and schedules while establishing key Performance Indicators (KPIs) to measure and monitor project progress. 
                    Collaborated in Scrum of Scrums and shared team progress, called out blockers, addressed impediments, resolved conflicts, and presented achieved milestones for Mercede-Benz USA at ATCS, UHCSR, UnderArmour, and Symitar at HARMAN.</li>
                    <li>
                        Collaborated  with engineering teams on successful Sprint demos to stakeholders and ensured that Change requests are planned for out of scope feedbacks .
                    
                    </li>
                    <li>
                        Ensured effective communication between team members and stakeholders.
                    </li>
                    <li> Defined stories in Jira and worked with engineering teams on their Sprint planning.</li>
                </ul>
        </div>
         <div v-if="n==4">
            Hello
        </div>
         <div v-if="n==5">
            <ul>
    <li>Developed UI modules for UHCSR’s claim portal, GE Medical’s Patient Portal, Chase’s Internet Banking module, Maritz’s loyalty rewards portal for its clients using React, Angular, AngularJS, EmberJS, PolymerJS, jQuery, HTML5, CSS3, Saas, and Less at HARMAN and PHOTON.</li>
    <li>Developed Hybrid mobile apps using Ionic 4, React Native, and packaging Angular 2/4 and VueJS SPAs using Apache Cordova for Symitar at HARMAN, Nike, and Maritz at PHOTON and Crisptag Technologies.</li>
    <li>Designed REST, gRPC, SOAP API contracts for backend integration using OpenAPI, Swagger, Postman Enterprise, and ReadyAPI at VIZIO, Ford Motors, ATCS, and Crisptag Technologies.</li>
    <li>Implemented REST APIs using Python with FastAPI, Node.js with Express and Fastify, and Rust with reqwest at VIZIO, Ford Motors, ATCS, and Crisptag Technologies.</li>
    <li>Integrated SalesForce, ZOHO CRM, ZOHO Books, and QuickBooks using Microsoft Power Automate for building ERPs and billing systems for clients at Crisptag Technologies.</li>
    <li>Developed WebEx’s notification module using AngularJS, Kafka, and Apache Spark for CISCO at Capgemini India.</li>
    <li>Implemented data lakes using AWS Kinesis, S3, and Aurora at ATCS and Crisptag Technologies.</li>
    <li>Developed CI/CD pipelines using Jenkins, Azure Pipelines, GitHub Actions, CircleCI, and Bash/Zsh/Tcsh shell scripts for multiple projects at VIZIO, Ford Motors, ATCS, and Crisptag Technologies, GLOBALFOUNDRIES, Virage Logic, ARM, and AMD.</li>
    <li>Orchestrated AWS, Azure, and GCP cloud infrastructures using Terraform, Ansible, OpenShift, Puppet, and Chef at VIZIO, Ford Motors, ATCS, UnderArmour, and Symitar at HARMAN and Crisptag Technologies.</li>
    
    <li>Developed modules of cloud telephony SaaS product to route calls using FreeSwitch.</li>
    <li> Implemented store reciepts parser to prepare year end expense summary using Azure Logic Apps and Azure AI Vision</li>
    <li> Developed billing system to compute agregate SaaS consumption of customers from vendor invoices, and, raise consolidated invoices using Azure Logic Apps,   Azure AI Vision and ZOHO Books at Crisptag Technologies.  </li>
    
        
    <li>
        
WYSIWYG editor
JSP and PHP based WYSIWYG editor for Microsoft Internet explorer 5.5 and Netscape Navigator 6.
    </li>
</ul>   
        </div>
         <div v-if="n==6">
            <ul>
                    <li>
                Quickly grasped details of Timing Analysis tools (Primetime®), Simulation tools (HSPICE®, HSIM®), Layout tools (Virtuoso®, Laker®), Physical verification tools (Hercules®, Caliber®, Assura®), parasitic extraction tools ( Star-RCXT®), PnR tools (SoC Encounter®) and automated Custom IC design flow using Tcl/Tk, Perl, Python and JAVA AWT and Swing at Virage Logic, ARM and AMD.</li>
                <li>Managed FlexLM® based EDA licenses at Texas Instruments, GLOBALFOUDNRIES, Virage Logic, ARM and AMD and automated their deployment.</li>
                    <li>Managed LSF® and FlowTracer® environments at Texas Instruments, GLOBALFOUDNRIES, Virage Logic, ARM and AMD in deep collaboration with IT Infrastructure team, and , automated their deployment.</li>
                        <li>	Installed and maintained EDA tools from Cadence, Synopsys, Mentor Graphics, Silvaco EDA tools in Linux, Solaris and HP-UX environment, and, integrated them with FlexLM licensing, LSF/FlowTracer for seamless run at Virage Logic, ARM, ST-Ericson, GLOBALFOUNDRIES. Managed cross-site sync of installed EDA softwares and their environment wrappers using rsync and custom scripts at Virage Logic. Received Employee of month award at Virage Logic for this effort. Additionally, Developed EDA tools qualification suite at Virage Logic.</li>
                            <li>	Developed web-based dashboards for EDA licenses reporting using PHP at Texas Instruments, GLOBALFOUDNRIES, Virage Logic, ARM and AMD.</li>
                                <li>	Automated BugZilla bug filing on error in SoC Design Flow during runtime to speed up the tapeout at AMD and received recognition for hard work.</li>
                                    <li>	Administrated Git, DesignSync®, Perforce® and CVS for code management and checks at GLOBALFOUDNRIES, Virage Logic, ARM and AMD.</li>
                                        <li>	Developed multiple utilities in Tcl/Tk at GLOBALFOUDNRIES to automate post tapeout flow. </li>
                                            <li>	Developed and Managed PDKs at ST-Ericson, Virage Logic, ARM and AMD.</li>
                                                <li>	Developed Fluid GuardRing, Yank and Paste modules of Virtuso® as SMTS at Cadence Design Systems. </li>
                                                    <li>	Managed Tower, SMIC, UMC, Jazz, Sony, Samsung PDKs at Virage Logic. </li>
                                                        <li>	Managed POSIX ACLs to ensure adherence to US Export Control laws at GLOBALFOUDNRIES, Virage Logic, and AMD.</li>
        
                                                        </ul>
        </div>
        </v-container>
      </v-tabs-window-item>
    </v-tabs-window>
  </v-card>

</template>
<script>
  export default {
    data: () => ({
      tab: null,
    }),
  }
</script>
