
<script>
export default {
  data() {
    return {
      myData: [],
      msg: "ALLEGHENY COLLEGE",
    };
  },
  created() {
    this.fetchData();
  },
  methods: {
    async fetchData() {
      try {
        const response = await fetch('vue-project/src/data/data.json');
        this.myData = await response.json();
      } catch (error) {
        console.error('Error fetching data:', error);
      }
    },
  },
};
</script>

<template>
  <div class="greetings">
    <h1 class="gold">{{ msg }}</h1>
    <div>
      <ul>
        <li v-for="item in myData" :key="item.id">{{ item.name }}</li>
      </ul>
    </div>
    <h3>
      Department of Computer and Information Science
      <a href="https://www.cs.allegheny.edu/teaching/bulletin/" target="_blank" rel="noopener">cs.allegheny.edu</a> +
      <a href="https://catalog.allegheny.edu/content.php?catoid=44&navoid=1542" target="_blank"
        rel="noopener">Interdisciplinary Studies</a>.
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {

  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
