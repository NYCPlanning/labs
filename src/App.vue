<template>
  <div class="container-fluid">
    <div id="homepage-cover">
    </div>
    <div class="row mt-3">
      <div class="col-9 mx-auto">
        <div class="row justify-content-between">
          <div class="col">
            <router-link to="/">
              <img
                alt="NYC Planning"
                src="https://raw.githubusercontent.com/NYCPlanning/dcp-logo/master/dcp_logo_black_772.png"
                style="width: 75px"
              />
              <span
                class="text-black text-large"
              >
                &nbsp; Planning Labs
              </span>
            </router-link>
          </div>
          <div class="col-2">
            <div class="row justify-content-between">
              <router-link
                to="/about"
                class="text-white"
              >
                About
              </router-link>
              <router-link
                to="/about"
                class="text-white"
              >
                Projects
              </router-link>
            </div>
          </div>
        </div>  
      </div>
    </div>
    <div class="row">
      <div class="col">
        <router-view/>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
  @import './styles/custom-bootstrap';
</style>
