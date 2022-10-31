<template>
  <div>
    index<br />
    <NuxtLink to="/about">about</NuxtLink>
    <NuxtLogo />
    <BaseHeader />
  </div>
</template>

<script>
export default {
  asyncData() {
    console.log('asyncData')
  },
  created() {
    console.log('created')
  },
  fetch(context) {
    console.log('fetch')
    console.log(context.route)
  },
}
</script>
