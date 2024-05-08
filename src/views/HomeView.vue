<script setup>
import NavComponent from '@/components/NavComponent.vue'
import AboutComponent from '@/components/AboutComponent.vue';
import QualitiesComponent from '@/components/QualitiesComponent.vue';
import TechnologiesComponent from '@/components/TechnologiesComponent.vue';
import PossibilitiesComponent from '@/components/PossibilitiesComponent.vue';
import PackagesComponent from '@/components/PackagesComponent.vue';
import ProjectsComponent from '@/components/ProjectsComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
</script>

<template>
  <nav-component></nav-component>
  <about-component></about-component>
  <qualities-component></qualities-component>
  <technologies-component></technologies-component>
  <possibilities-component></possibilities-component>
  <packages-component></packages-component>
  <projects-component></projects-component>
  <footer-component></footer-component>
</template>

<style>
h1 {
  color: #000;
}
</style>