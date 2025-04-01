<script setup>
import BaseButton from './UI/BaseButton.vue'
import BaseAlert from './UI/BaseAlert.vue'
import BaseBadge from './UI/BaseBadge.vue'
</script>
<template>
  <!-- grid container -->
  <main class="component-grid">
    <!-- component group (grid item) -->
    <section class="component-card">
      <h2>버튼</h2>
      <BaseButton variant="primary">Primary</BaseButton>
      <BaseButton variant="outline">Outline</BaseButton>
      <BaseButton variant="pill">Pill</BaseButton>
    </section>
    <section class="component-card">
      <h2>알림창</h2>
      <BaseAlert variant="success">success message</BaseAlert>
      <BaseAlert variant="warning">warning message</BaseAlert>
      <BaseAlert variant="error">error message</BaseAlert>
    </section>
    <section class="component-card">
      <h2>배지</h2>
      <BaseBadge variant="success">Success</BaseBadge>
      <BaseBadge variant="number">3</BaseBadge>
    </section>
  </main>
</template>
