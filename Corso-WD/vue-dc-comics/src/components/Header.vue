<template>
  <header>
      <section class="img-section">
          <div class="img-box"></div>
      </section>
      <section class="nav-section">
          <ul class="flex">
              <li></li>
              <li></li>
              <li></li>
              <li></li>
              <li></li>
              <li></li>
              <li></li>
              <li></li>
              <li></li>
              <li></li>
              <li></li>
          </ul>
      </section>
  </header>
</template>

<script>


export default {
    name: 'Header',
    data(){
        return {
            navLink: [
                {
                    text: 'CHARACTERS',
                    url: '/',
                    current: true,
                },
                {
                    text: 'COMICS',
                    url: '/',
                    current: true,
                },
                 {
                    text: 'MOVIES',
                    url: '/',
                    current: true,
                },
                 {
                    text: 'TV',
                    url: '/',
                    current: true,
                },
                 {
                    text: 'GAMES',
                    url: '/',
                    current: true,
                },
                 {
                    text: 'COLLECTIBLES',
                    url: '/',
                    current: true,
                },
                 {
                    text: 'VIDEOS',
                    url: '/',
                    current: true,
                },
                 {
                    text: 'FANS',
                    url: '/',
                    current: true,
                },
                 {
                    text: 'NEWS',
                    url: '/',
                    current: true,
                },
                 {
                    text: 'SHOP',
                    url: '/',
                    current: true,
                },
            ]
        }
    }
}
</script>

<style scoped lang='scss'>
   @import '@/components/header.scss'
</style>