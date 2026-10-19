<template>
  <div class="slidev-layout cover">
    <BrandLogo />
    <div class="my-auto">
      <slot />
    </div>
    <BrandBanner />
  </div>
</template>

<style scoped>
.cover {
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
}

.cover :deep(h1) {
  font-size: 3.2em;
  border-bottom: 4px solid var(--skillforge-blue);
  display: inline-block;
  padding-bottom: 0.2em;
  margin-left: auto;
  margin-right: auto;
}
</style>