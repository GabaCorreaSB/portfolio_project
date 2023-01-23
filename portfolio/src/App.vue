<template>
  <div>
    <div class="header">
      <h1>My Portfolio</h1>
      <nav>
        <router-link to="/">HomePage</router-link>
        <router-link to="/projects">ProjectsPage</router-link>
        <router-link to="/skills">SkillsPage</router-link>
        <router-link to="/contact">ContactPage</router-link>
      </nav>
    </div>
    <router-view />
    <div>
    <HomePage />
    <ProjectsPage />
    <SkillsPage />
    <ContactPage />
    </div>
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue'
import ProjectsPage from './components/ProjectsPage.vue'
import SkillsPage from './components/SkillsPage.vue'
import ContactPage from './components/ContactPage.vue'

export default {
  components: {
    HomePage,
    ProjectsPage,
    SkillsPage,
    ContactPage
  }
}
</script>

