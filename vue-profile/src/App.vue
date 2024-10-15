<script setup>
import CareerLine from './components/CareerLine.vue';
import RecentEmployments from './components/RecentEmployments.vue';
import Certifications from './components/Certifications.vue';
import TechnicalSkills from './components/TechnicalSkills.vue';
import Accomplishments from './components/Accomplishments.vue';
import ComingSoon from './components/ComingSoon.vue';
</script>


  <template>
    <ComingSoon />
    <h2> Amit Gupta </h2> 
    <h3> <a href="resumes/Resume_AmitGupta_SolutionArchitect.pdf" >Multi-cloud Solutions Architect</a> | <a href="resumes/Resume_AmitGupta_EngineeringManager.pdf" >Engineering Manager</a> | <a href="resumes/AmitGupta_TechnicalProjectManager.pdf" >Technical Project Manager </a>  | <a href="resumes/Resume_AmitGupta_CAD.pdf" >CAD & EDA Design Methodologies Engineer </a> | Ex-SaaS Startup Founder & Builder</h3>
    <div class="summary"><i> "Brings comprehensive skill set, encompassing both broad cross-functional expertise and deep specialization in key areas.".<br>"Consistently recognized for ability to rapidly explore, learn and deliver results across diverse domains,and, thinking out of the box."
    </i></div>
    <Certifications  />
    <br>
    <RecentEmployments  />
    <br>
    <Accomplishments  />
    <br>
    <CareerLine />
    <br>
    <TechnicalSkills  />
    </template>