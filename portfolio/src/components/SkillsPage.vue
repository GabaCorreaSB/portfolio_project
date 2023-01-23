<template>
  <div>
    <h2>Skills</h2>
    <ul>
      <li v-for="skill in skills" :key="skill.id">{{ skill.name }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      skills: [
        { id: 1, name: 'Vue.js' },
        { id: 2, name: 'JavaScript' },
        { id: 3, name: 'HTML' },
        { id: 4, name: 'CSS' },
        // more skills
      ]
    }
  }
}
</script>

