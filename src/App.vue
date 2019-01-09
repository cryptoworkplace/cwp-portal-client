<template>
  <div class="m-grid m-grid--hor m-grid--root m-page" id="app">
    <v-header/>

    <!-- begin::Body -->
    <div class="m-grid__item m-grid__item--fluid m-grid m-grid--ver-desktop m-grid--desktop m-body">
      <!-- BEGIN: Left Aside -->
      <button class="m-aside-left-close m-aside-left-close--skin-dark" id="m_aside_left_close_btn">
        <i class="la la-close"></i>
      </button>
      <v-aside/>
      <!-- END: Left Aside -->

      <div class="m-grid__item m-grid__item--fluid m-wrapper">
        <!-- BEGIN: Subheader -->
        <div class="m-subheader">
          <div class="d-flex align-items-center">
            <div class="mr-auto">
              <h3 class="m-subheader__title m-subheader__title--separator">Dashboard</h3>
            </div>
          </div>
        </div>
        <!-- END: Subheader -->

        <div class="m-content">
          <router-view/>
        </div>
      </div>

    </div>
    <!-- end:: Body -->

    <v-footer/>
  </div>
</template>

<script>
  import Header from '@/components/Header/Header.vue'
  import Footer from '@/components/Footer.vue'
  import AsideMenu from '@/components/AsideMenu.vue'

  export default {
    name: 'App',
    components: {
      'v-header': Header,
      'v-footer': Footer,
      'v-aside': AsideMenu
    },
  }
</script>

<style lang="scss">
  @import "/sass/style.scss";
  @import "/assets/fonts/flaticon/css/flaticon.css";
</style>
