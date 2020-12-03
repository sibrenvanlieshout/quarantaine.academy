<template>
  <b-card
    style="max-width: 50rem;"
    class="m-3"
  >
    <b-card-title>            
        Current Polis
    </b-card-title>
    <b-card-body>
        <div class='polis' data-conversation_id='6m6uxy8et6'></div>
    </b-card-body>
  </b-card>
</template>

<script lang="ts">
export default {
  name: "PolisCard", 
  mounted() {
        let polisScript = document.createElement('script')
        polisScript.setAttribute('src', 'https://pol.is/embed.js')
        document.head.appendChild(polisScript)
    },   
}
</script>

<style scoped>
</style>