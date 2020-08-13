<template>
  <div class="about">
    <h1>This is an about page</h1>
    <test-comp></test-comp>
  </div>
</template>

<script>
import aa from '@/components/test_file.vue'


export default {
    name: "About",
    components: {
        'test-comp': aa
    }
}
</script>