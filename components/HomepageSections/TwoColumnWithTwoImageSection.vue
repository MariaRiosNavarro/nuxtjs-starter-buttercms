<template>
  <section :id="fields.scroll_anchor_id" class="cta-section">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 order-last order-lg-first">
          <img :src="fields.image1" alt="" />
        </div>
        <div class="col-lg-6">
          <img :src="fields.image2" alt="" />
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const props = defineProps(["fields"]);
</script>
