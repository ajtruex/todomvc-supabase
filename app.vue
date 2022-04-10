<template>
  <div>
    <h1>TodoMVC Supabase</h1>
    <p>{{ supabaseUrl}}</p>
  </div>
</template>

<script setup>
const config = useRuntimeConfig()
const {supabaseUrl} = config

console.log(config)
</script>