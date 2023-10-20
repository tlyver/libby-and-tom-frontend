<template>
  <div class="item">
    <div class="heading">
      <slot name="heading"></slot>
    </div>
    <div class="details">
      <slot></slot>
    </div>
  </div>
</template>

<style scoped>
.item {
  margin-top: 2rem;
  display: flex;
  flex-direction: column;
}

.item > * {
  flex: 1;
  padding: .5rem 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

.item > *:first-child {
  border-right: 1px solid var(--vt-c-black);
}

@media (min-width: 769px) {
  .item {
    flex-direction: row;
  }
}

i {
  display: flex;
  place-items: center;
  place-content: center;
  width: 32px;
  height: 32px;

  color: var(--color-text);
}

h3 {
  font-size: 1.2rem;
  font-weight: 500;
  margin-bottom: 0.4rem;
  color: var(--color-heading);
}

</style>
