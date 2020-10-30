<template>
  <div>
    <b-jumbotron fluid container-fluid="md" bg-variant="white" border-variant="dark" class="full-height">
      <template #header>A and B interfaces</template>

      <template #lead>
        The A version has cards with the checkout button below the cards (the user has to scroll
         down to checkout) and the B version just has cacti in columns with centered text, with the cart icon on the upper right corner of the screen.
         The A version has the "number" in cart text red in color, to attract the user and be distinct on the website.
      </template>
      <b-container class="bv-example-row">
        <b-row  class="mb-5" align-v="center">
          <b-col>
            <b-img :src="require('../assets/A.png')" fluid alt="Responsive image"></b-img>
            <p class="m-4 h5 font-weight-light text-center">A version</p>
          </b-col>
          <b-col>
            <b-img :src="require('../assets/B.png')" fluid alt="Responsive image"></b-img>
            <p class="m-4 h5 font-weight-light text-center">B version</p>
          </b-col>
        </b-row>

        <b-row  class="mb-5">
          <h1>Data Collection Process</h1>
          <p class="m-4 h5 font-weight-light">
          The link was shared to the peers for data 
          collection.
          The data for this website was collected from the around 16 user session clicks by people in the studio for CSCI 1300 
          and extra 16 user clicks 
          from people not in CSCI 1300. So there are a total of 32 user session clicks. 
          Regardless of which version a user gets, their task should be to fill their cart with at least $150 of cacti/succulents.
          </p>
        </b-row>
      </b-container>
    
    </b-jumbotron>
  </div>
</template>

<script>

export default {
  name: 'AB',
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
