<template>
  <div class="bg-blue-500 p-4 border">
    <div class="p-4 border">
      <slot name="sidebar"/>
    </div>
    <div class="border p-4">
      Company Layout
      <slot/>
    </div>
  </div>
</template>
