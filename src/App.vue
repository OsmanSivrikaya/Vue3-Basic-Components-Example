<template>
  <app-header></app-header>
  <div class="container">
    <h3> Deneme </h3>
    <p>asdasd</p>
  </div>
  <counterItem></CounterItem>
</template>
<script>
  import CounterItem from "@/components/CounterItem.vue";
  export default{
    components: {
      CounterItem : CounterItem,
    },
  }
</script>