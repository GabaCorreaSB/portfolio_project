<template>
  <div>
    <h2>Projects</h2>
    <ul>
      <li v-for="project in projects" :key="project.id">
        <h3>{{ project.name }}</h3>
        <p>{{ project.description }}</p>
        <a :href="project.demoLink" target="_blank">Live Demo</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      projects: [
        { id: 1, name: 'Project 1', description: 'A sample project', demoLink: 'https://project1.com' },
        { id: 2, name: 'Project 2', description: 'Another sample project', demoLink: 'https://project2.com' },
        // more projects
      ]
    }
  }
}
</script>

