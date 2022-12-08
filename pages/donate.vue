<template>
  <div>
    <h1>Donate with Bitcoin</h1>
    <p>
      Thank you for considering a donation to support our work. You can use
      Bitcoin to make a secure and anonymous donation to our organization.
    </p>
    <a href="bitcoin:{{ bitcoinAddress }}?amount={{ donationAmount }}">
      Donate with Bitcoin
    </a>
  </div>
</template>

<script>
export default {
  data () {
    return {
      bitcoinAddress: '1BvBMSEYstWetqTFn5Au4m4GFg7xJaNVN2',
      donationAmount: 0.01
    }
  }
}
</script>

<style>
</style>