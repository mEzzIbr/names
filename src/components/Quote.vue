<template>
  <section class="quote">
  <div class="quote-content">
    {{ quote.content }}
<div class="quote-info">
  <div class="quote-anime">
    {{ quote.anime }}
  </div>
  <div class="quote-author">
    {{ quote.char }}

  </div>

</div>

  </div>

    {{ quote.test }}
  </section>

</template>

<script>
export default {
  props: ['quote']
}

</script>

<style scoped>
.quote {
  position: relative;
  margin: 0 auto;
  padding: 32px;
  max-width: 720px;


}
.quote-content {
  position: relative;
  font-size: 28px;
  font-weight: 600;
  padding: 48px 32px;
  border-radius: 16px ;
  background-color: darkslategray;
  color: #84afff;
}
.quote-info {
  position: relative;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  padding: 32px;
  font-weight: 300;
}

</style>
