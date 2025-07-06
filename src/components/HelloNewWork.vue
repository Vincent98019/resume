<script setup>
import BasicInformation from "@/components/BasicInformation.vue";
import ProfessionalSkills from "@/components/ProfessionalSkills.vue";
import WorkExperience from "@/components/WorkExperience.vue";
import ProjectExperience from "@/components/ProjectExperience.vue";
import EducationalBackground from "@/components/EducationalBackground.vue";
import PersonalSummary from "@/components/PersonalSummary.vue";
import {onMounted} from "vue";

async function getData() {
  await fetch('https://healtrack.cn:8500/public/resume/count');
}

onMounted(async () => {
  await getData();
});

</script>

<template>
  <div>
    <BasicInformation/>
    <div class="size-div-1"></div>
    <ProfessionalSkills/>
    <div class="size-div-2"></div>
    <WorkExperience/>
    <div class="size-div-2"></div>
    <ProjectExperience/>
    <div class="size-div-2"></div>
    <EducationalBackground/>
    <div class="size-div-1"></div>
    <PersonalSummary/>
    <div class="size-div-3"></div>
  </div>
</template>

<style scoped>

.size-div-1 {
  height: 30px;
}

.size-div-2 {
  height: 10px;
}

.size-div-3 {
  height: 100px;
}
</style>
