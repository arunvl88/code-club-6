<template>
    <div>
      <button @click="processDonation">Donate with Bitcoin</button>
    </div>
  </template>
  
  <script>
  export default {
    methods: {
      processDonation() {
        // Replace with your BitPay payment button code
        const paymentButtonCode = '<!-- Your BitPay payment button code here -->';
        const paymentWindow = window.open('', '_blank');
        paymentWindow.document.write(paymentButtonCode);
      }
    }
  }
  </script>
  
