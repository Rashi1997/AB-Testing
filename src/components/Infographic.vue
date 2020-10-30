<template>
  <div>
    <b-jumbotron fluid container-fluid="md" bg-variant="white" border-variant="dark" class="full-height">
      <template #header>Infographic</template>

      <template #lead>
        
      </template>
      <b-container class="bv-example-row d-flex justify-content-center">
        <b-row  class="mb-5" align-h="center">
          <b-col>
            <b-img class="image" :src="require('../assets/infographic.png')" fluid alt="Responsive image"></b-img>
            <p class="m-4 h5 font-weight-light text-center">Infographic for conclusions</p>
          </b-col>
        </b-row>
      </b-container>
    
    </b-jumbotron>
  </div>
</template>

<script>

export default {
  name: 'Infographic',
  components: {
  }
}
</script>

<style scoped>
  .full-height {
    padding-bottom: 15rem;
    margin-bottom: 0;
    border: 0!important;
    height: 100%;
  }
  .image {
    max-height: 100vh;
  }
</style>
