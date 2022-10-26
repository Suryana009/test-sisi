<template>
    <b-breadcrumb :items="items"></b-breadcrumb>
</template>
  
<script>
    export default {
      data() {
        return {
          items: [
            {
              text: 'Halaman Muka',
              href: '#'
            },
            {
              text: 'Akun Saya',
              active: true
            }
          ]
        }
      }
    }
</script>