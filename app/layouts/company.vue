<template>
  <div class="p-4 ring-black ring grid grid-cols-[auto_1fr]">
    <div class="p-4 border">
      <slot name="sidebar"/>
    </div>
    <div class="border p-4">
      <h1 class="text-3xl mb-16">
        Company Layout
      </h1>
      <slot/>
    </div>
  </div>
</template>
