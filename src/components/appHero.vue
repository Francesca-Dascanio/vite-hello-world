<script>
export default {
  data() {
    return {
        image:'https://www.easyjet.com/ejcms/cache/medialibrary/Images/JSS/Destinations/Hero/Poland_Krakow_3840x2160.jpg?mw=1920&hash=CEE15B2B5639A7AB9B79197411EA9ECCFD91BADC'
    }
  }
}
</script>

<template>
    <img :src="image" alt="cracovia">
</template>

<style scoped>
    img {
        max-width: 1280px;
        height: 600px;
        margin: 0 auto;
        padding: 2rem;
    }
</style>