<template>
  <div class="slidev-layout section">
    <BrandLogo />
    <div class="my-auto">
      <slot />
    </div>
    <BrandBanner />
  </div>
</template>

<style scoped>
.section {
  display: flex;
  flex-direction: column;
  justify-content: center;
  background: var(--skillforge-dark);
}

.section :deep(h1),
.section :deep(h2) {
  color: white;
  font-size: 2.8em;
}

.section :deep(p) {
  color: #cfd8dc;
}
</style>