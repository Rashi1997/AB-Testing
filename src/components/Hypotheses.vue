<template>
  <div>
    <b-jumbotron fluid container-fluid="md" bg-variant="white" border-variant="dark" class="full-height">
      <template #header>Creating Hypotheses</template>

      <template #lead>
        The task at hand is to put >$150 worth of cacti in the cart. The <b>time to complete</b> this task is calculated
          as the difference between <b>click time</b> and the <b>page load time</b>. The <b>return rate</b> is the number of times a user 
          returned to the page.
      </template>
      <b-container class="bv-example-row">
        <b-row  class="mb-5">
          <b-col>
            <h1>Time to Completion</h1>
            <p class="m-4 h5 font-weight-light">
              <mark>
                The null hypotheses for time to completion is that A version will take more time than the version B
              </mark>
              which is used to prove the alternative hypotheses that A takes less time to complete than B.
            </p>
            <p class="m-4 h5 font-weight-light">
              The reason behind the alternative hypotheses is that the version A has cards which with red highlighted bigger 
              price font size and red highlighted number in cart, which is distinct from the other text
              and helps the user to achieve the task. Also in version A the checkout button is larger and just below the cards and easier 
              to find and the user can directly checkout more conveniently than in version B where the cart icon
              is in the upper right corner.
            </p>
          </b-col>
          <b-col>
            <h1>Return Rate</h1>
            <p class="m-4 h5 font-weight-light">
              <mark>
                The null hypotheses for return rate is that A version will have more return rate than the version B,
              </mark>
              which is used to prove the alternative hypotheses that A has less return rate than B.
            </p>
            <p class="m-4 h5 font-weight-light">
              The reason behind the alternative hypotheses is that the version A has cards which with red highlighted bigger 
              price font size and red highlighted number in cart, which is distinct from the other text
              and helps the user to achieve the task and not return back to add more cacti.
            </p>
          </b-col>
        </b-row>
      </b-container>
    
    </b-jumbotron>
  </div>
</template>

<script>

export default {
  name: 'Hypotheses',
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
