<template>
  <div class="container">
    <div class="inner__container">
      <img class="inner__container__logo" src="../assets/logo.svg" />
      <h2 class="inner__container__title">Job Description Generator</h2>
      <h4 class="inner__container__intro">
        Fill the form below to generate job description template for your tech
        startup.
      </h4>
      <Form/>
      <h3 class="inner__container__intro">Easy JD from Product Cycle Africa</h3>
      <Footer/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Form from "@/components/Form.vue";
//import Form from '@/components/Footer.vue';
import Footer from '../components/Footer.vue';

export default {
  name: "Home",
  components: {
    Form,
    Footer
  },
};
</script>
