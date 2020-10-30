<template>
  <div>
    <b-jumbotron fluid container-fluid="md" bg-variant="white" border-variant="dark" class="full-height">
      <template #header>Takeaways</template>

      <template #lead>
           The A/B testing in industry takes over millions of user data to calculate the statistical effect of the change. Here we are taking very few
        user sessions which is not enough to reflect small design changes like change of the text color, change of location of the checkout 
        icon. If there was something drastic like difficult to find checkout option of a version, we would see some significance in data to reject the null
        hypotheses.
        <br><br>
         As the data collected was not statistically significant we cannot draw any conclusions for design principles from the stated hypotheses.
      </template>
    
    </b-jumbotron>
  </div>
</template>

<script>

export default {
  name: 'Takeaways',
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
</style>
