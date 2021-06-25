<template>
  <div>
    <base-header
      class="header pb-8 pt-5 pt-lg-8 d-flex align-items-center"
      style="
        min-height: 600px;
        background-image: url();
        background-size: cover;
        background-position: center top;
      "
    >
      <!-- Mask -->
      <span class="mask bg-dark opacity-8"></span>
      <!-- Header container -->
      <div class="container-fluid d-flex align-items-center">
        <div class="row">
          <div class="col-lg-7 col-md-10">
            <h1 class="display-2 text-white">Hi, it's Gavin</h1>
            <p class="text-white mt-0 mb-5">
              Feel free to check out some of my cool projects. Or, keep browsing
              to see some of the things I like!
            </p>
          </div>
        </div>
      </div>
    </base-header>

    <div class="container-fluid mt--7">
      <div class="row">
        <div class="col-xl-4 order-xl-2 mb-5 mb-xl-0">
          <div class="card card-profile shadow">
            <div class="row justify-content-center">
              <div class="col-lg-3 order-lg-2">
                <div class="card-profile-image">
                  <a href="#">
                    <img
                      src="img/theme/profile_small.jpg"
                      class="rounded-circle"
                    />
                  </a>
                </div>
              </div>
            </div>
            <div
              class="card-header text-center border-0 pt-8 pt-md-4 pb-0 pb-md-4"
            >
              <div class="d-flex justify-content-between">
                <base-button size="sm" type="default" class="mr-4"
                  >My CV</base-button
                >
                <base-button size="sm" type="info" class="float-right"
                  >Contact</base-button
                >
              </div>
            </div>
            <div class="card-body pt-0 pt-md-4">
              <div class="row">
                <div class="col">
                  <div
                    class="card-profile-stats d-flex justify-content-center mt-md-5"
                  ></div>
                </div>
              </div>
              <div class="text-center">
                <h3>Gavin Wu<span class="font-weight-light">, 19</span></h3>
                <div class="h5 font-weight-300">
                  <i class="ni location_pin mr-2"></i>London, United Kingdom
                </div>
                <div class="h5 mt-4">
                  <i class="ni business_briefcase-24 mr-2"></i>Imperial College
                  London
                </div>
                <div>
                  <i class="ni education_hat mr-2"></i>MEng, Computer Science
                  (3rd Year)
                </div>
                <hr class="my-4" />
                <p>
                  As an upcoming software engineer, I needed somewhere to
                  showcase my projects. I'm also trying to keep up to date with
                  a range of other interests, these include: business,
                  investing, reading personal development books and I'm also an
                  art fan.
                </p>
              </div>
            </div>
          </div>
        </div>

        <div class="col-xl-8 order-xl-1">
          <card shadow type="secondary">
            <template v-slot:header>
              <div class="bg-white border-0">
                <div class="row align-items-center">
                  <div class="col-8">
                    <h3 class="mb-0">My account</h3>
                  </div>
                  <div class="col-4 text-right">
                    <a href="#!" class="btn btn-sm btn-primary">Settings</a>
                  </div>
                </div>
              </div>
            </template>
            <div class="row">
              <div class="col-xl-6 col-lg-12 pb-xl-3">
                <stats-card
                  title="Total traffic"
                  type="gradient-red"
                  sub-title="350,897"
                  icon="ni ni-active-40"
                  class="mb-4 mb-xl-0"
                >
                  <template v-slot:footer>
                    <span class="text-success mr-2">
                      <i class="fa fa-arrow-up"></i> 3.48%
                    </span>
                    <span class="text-nowrap">Since last month</span>
                  </template>
                </stats-card>
              </div>
              <div class="col-xl-6 col-lg-12">
                <stats-card
                  title="Total traffic"
                  type="gradient-orange"
                  sub-title="2,356"
                  icon="ni ni-chart-pie-35"
                  class="mb-4 mb-xl-0"
                >
                  <template v-slot:footer>
                    <span class="text-success mr-2">
                      <i class="fa fa-arrow-up"></i> 12.18%
                    </span>
                    <span class="text-nowrap">Since last month</span>
                  </template>
                </stats-card>
              </div>
              <div class="col-xl-6 col-lg-12">
                <stats-card
                  title="Sales"
                  type="gradient-green"
                  sub-title="924"
                  icon="ni ni-money-coins"
                  class="mb-4 mb-xl-0"
                >
                  <template v-slot:footer>
                    <span class="text-danger mr-2">
                      <i class="fa fa-arrow-down"></i> 5.72%
                    </span>
                    <span class="text-nowrap">Since last month</span>
                  </template>
                </stats-card>
              </div>
              <div class="col-xl-6 col-lg-12">
                <stats-card
                  title="Performance"
                  type="gradient-info"
                  sub-title="49,65%"
                  icon="ni ni-chart-bar-32"
                  class="mb-4 mb-xl-0"
                >
                  <template v-slot:footer>
                    <span class="text-success mr-2">
                      <i class="fa fa-arrow-up"></i> 54.8%
                    </span>
                    <span class="text-nowrap">Since last month</span>
                  </template>
                </stats-card>
              </div>
            </div>
          </card>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "user-profile",
  data() {
    return {
      model: {
        username: "",
        email: "",
        firstName: "",
        lastName: "",
        address: "",
        city: "",
        country: "",
        zipCode: "",
        about: "",
      },
    };
  },
};
</script>
<style></style>
