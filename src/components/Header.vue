<template>
  <header id="m_header" class="m-grid__item m-header" m-minimize-offset="200" m-minimize-mobile-offset="200">
    <div class="m-container m-container--fluid m-container--full-height">
      <div class="m-stack m-stack--ver m-stack--desktop">
        <!-- BEGIN: Brand -->
        <div class="m-stack__item m-brand  m-brand--skin-dark ">
          <div class="m-stack m-stack--ver m-stack--general">
            <div class="m-stack__item m-stack__item--middle m-stack__item--center m-brand__logo">
              <a href="index.html" class="m-brand__logo-wrapper">
                <img alt="" src="assets/demo/media/img/logo/logo.png" />
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

        </div>

      </div>
    </div>
  </header>
</template>

<script>
  export default {
    name: 'Header',
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
