<template>
</template>

<script>
export default {
  data() {
    return { 
      drawer: false,
      routes: [ 
      ],
      mobileRoutes: [
        { icon: "mdi-home", href: "/", label: "Home" }
      ]
    };
  }
};
</script>
<style>
  .bg-white {
        padding: 24px;
    background-color: rgba(255, 255, 255, 0);
    border: 1px solid rgba(141, 89, 255, 0.8);
    box-shadow: rgb(141 89 255) 0px 0px 15px inset;
    border-radius: 20px;
  }
  .text-gray-700{
    color:rgba(255, 255, 255, 0.7) !important;
  }
  .theme--light.v-card {
    background-color: #545454 !important;
    color: rgb(255 255 255 / 87%) !important;
}
.theme--light.v-card > .v-card__text, .theme--light.v-card > .v-card__subtitle {
    color: rgb(255 255 255 / 60%) !important;
}
.v-application .green--text.text--darken-1 {
    color: white !important;
    caret-color: white !important;
}
  .v-btn:not(.v-btn--round).v-size--default {
   /* height: 36px; */
    /* min-width: 64px; */
    /* padding: 0 16px; */
    /* width: 100%; */
    /* height: 60px; */
    /* margin-top: 10px; */
    /* margin-bottom: 5px; */
    background: linear-gradient(to right, rgb(147, 24, 128), rgb(142, 45, 226));
    color: white !important;
    /* font-size: 16px; */
    /* font-weight: bold; */
    border-radius: 99px;
}
  .v-application a {
    text-decoration: underline;
      color: white;
  }
  .title {
    @apply text-white text-lg font-semibold
  }
  .navlink {
    @apply text-white text-base
  }
  .navlink:link{
    @apply text-white text-base
  }
  .navlink:hover{
    @apply text-white text-base underline
  }
  .navlink:visited {
    @apply text-white text-base
  }
  .titleWidth{
  width: 400px !important;
}
.theme--light.v-application {
    background: #FFFFFF;
        background-color: #060826 !important;
}
</style>