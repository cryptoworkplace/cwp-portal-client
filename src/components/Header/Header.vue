<template>
  <header id="m_header" class="m-grid__item m-header" m-minimize-offset="200" m-minimize-mobile-offset="200">
    <div class="m-container m-container--fluid m-container--full-height">
      <div class="m-stack m-stack--ver m-stack--desktop">
        <!-- BEGIN: Brand -->
        <div class="m-stack__item m-brand  m-brand--skin-dark ">
          <div class="m-stack m-stack--ver m-stack--general">
            <div class="m-stack__item m-stack__item--middle m-stack__item--center m-brand__logo">
              <a href="/" class="m-brand__logo-wrapper">
                <img alt="" src="@/assets/demo/media/img/logo/logo.png" />
                <!--<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 492.84 445.26" fill="#525672" id="logo" height="44px">-->
                  <!--<path d="M279.74 222.15c0-30.23 25-55.53 55.36-55.22 32.81.33 55.83 26.19 55.8 56.11 0 30.33-25.48 55.52-55.87 55.29-30.88-.23-55.33-25.07-55.3-56.18M0 225.83c1.67 6.09 2.46 12.61 5.16 18.2 8.56 17.74 23.16 27 42.87 27.26 21.79.31 43.59.07 65.39.08h4.7a224.31 224.31 0 0 0 34.1 77.8H147c-18.34 0-36.7-.4-55 .27-20 .74-34.75 10.86-42.43 29.18-7.94 18.94-4.42 36.7 9.76 51.9 9.4 10.07 21.26 14.67 34.9 14.67 80.81 0 161.61.17 242.42-.06 38.6-.11 74.73-10.06 108.37-29a228.62 228.62 0 0 0 47-35.51L424 312.73c-28.31 27-62.68 39.39-102.33 35.34-33.76-3.45-61.59-18.84-83.54-44.75-40.28-47.54-37.85-119.88 4-166.11 42.55-47 126.56-59.52 182.76-4Q453.42 104.6 482 76c3.54-3.55 7.23-7 10.84-10.42v-.8C486.72 59.49 480.76 54 474.46 49 444.33 25 410.41 9.24 372.25 3.34a255.88 255.88 0 0 0-38-3.17C255.21-.1 176.15 0 97.1.05c-26.45 0-46.18 15.19-50.46 40-5.2 30.1 17.36 54.81 43.55 55.81 18.71.71 37.46.31 56.19.41h5.37c-2.87 4.68-5.37 8.69-7.81 12.72a209.3 209.3 0 0 0-25 61.66c-.86 3.75-2.36 4.71-6.08 4.69-22.32-.12-44.64-.19-67 .19S3.79 194 .74 216c-.16 1.17-.49 2.31-.74 3.47v6.38"></path>-->
                <!--</svg>-->
              </a>
            </div>
            <div class="m-stack__item m-stack__item--middle m-brand__tools">

              <!-- BEGIN: Responsive Aside Left Menu Toggler -->
              <a href="javascript:;" id="m_aside_left_offcanvas_toggle" class="m-brand__icon m-brand__toggler m-brand__toggler--left m--visible-tablet-and-mobile-inline-block">
                <span></span>
              </a>

              <!-- END -->

              <!-- BEGIN: Responsive Header Menu Toggler -->
              <a id="m_aside_header_menu_mobile_toggle" href="javascript:;" class="m-brand__icon m-brand__toggler m--visible-tablet-and-mobile-inline-block">
                <span></span>
              </a>

              <!-- END -->

              <!-- BEGIN: Topbar Toggler -->
              <a id="m_aside_header_topbar_mobile_toggle" href="javascript:;" class="m-brand__icon m--visible-tablet-and-mobile-inline-block">
                <i class="flaticon-more"></i>
              </a>

              <!-- BEGIN: Topbar Toggler -->
            </div>
          </div>
        </div>
        <!-- END: Brand -->
        <div class="m-stack__item m-stack__item--fluid m-header-head" id="m_header_nav">
          <!-- BEGIN: Horizontal Menu -->
          <button class="m-aside-header-menu-mobile-close  m-aside-header-menu-mobile-close--skin-dark" id="m_aside_header_menu_mobile_close_btn">
            <i class="la la-close"></i>
          </button>

          <v-hor-menu/>
          <!-- END: Horizontal Menu -->
          <!-- BEGIN: Topbar -->
          <v-top-bar/>
          <!-- END: Topbar -->
        </div>

      </div>
    </div>
  </header>
</template>

<script>
  import HorizontalMenu from '@/components/Header/HorizontalMenu.vue'
  import TopBar from '@/components/Header/TopBar.vue'


  export default {
    name: 'Header',
    components:{
      'v-hor-menu': HorizontalMenu,
      'v-top-bar': TopBar
    },
    data() {
      return {

      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .b-header {

  }
</style>
