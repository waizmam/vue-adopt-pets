<template>
  <div class="home">
    <h1>Adopt a new best friend</h1>
    <button class="btn btn-primary">Add New Pet</button>
  </div>
</template>

<script>

export default {
  name: 'home',
  data () {
    return {
      showPetForm: false
    }
  },
  methods: {
    togglePetForm () {
      this.showPetForm = !this.showPetForm
    }
  }
}
</script>
