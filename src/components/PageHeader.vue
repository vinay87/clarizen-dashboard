<template>
  <div class="page-header">
    <div>
      <h1 class="page-title">
        {{ title }}
      </h1>
      <div v-if="this.subtitle" class="page-description">
        {{ subtitle }}
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PageHeader',
  props: {
    title: String,
    subtitle: String
  }
}
</script>
