<template>
  <div>
    <b-jumbotron fluid container-fluid="md" bg-variant="dark" text-variant="white" border-variant="dark" class="full-height">
      <template #header>
        <span class="display-1">AB Testing</span>
      </template>

      <template #lead>
        <span class="h3">Performing an A/B test and statistical analysis to gather insight into two different UI designs. 
</span>
      </template>

      <hr class="my-4" style="color:white;">

      <p>
        The goal of this project ranges from creating two versions of a Cacti selling ecommerce website to creating hypotheses and finally
        drawing conclusions based on the statistical analysis. This link to the site below randomly picks A or B version which can be seen in
        the title of the tab.
      </p>
      <b-button variant="primary" href="https://thawing-sea-35748.herokuapp.com/">A/B interface</b-button>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: 'Introduction',
  components: {
  }
}
</script>

<style scoped>
  .full-height {
    height: 100%;
    padding-top: 9rem;
    padding-bottom: 15rem;
    margin-bottom: 0;
  }
  hr {
    border:0.01rem solid white;
  }
</style>
