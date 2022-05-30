<template>
  <div class="home">
    <HeaderEdu />
    <HomeEdu />
    <CounterEdu />
    <AboutEdu />
    <CoursesEdu />
    <TeachersEdu />
    <ReviewsEdu />
    <ContactEdu />
    <FooterEdu />
    <!-- <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderEdu from "@/components/HeaderEdu.vue";
import HomeEdu from "@/components/HomeEdu.vue";
import CounterEdu from "@/components/CounterEdu.vue";
import AboutEdu from "@/components/AboutEdu.vue";
import CoursesEdu from "@/components/CoursesEdu.vue";
import TeachersEdu from "@/components/TeachersEdu.vue";
import ReviewsEdu from "@/components/ReviewsEdu.vue";
import ContactEdu from "@/components/ContactEdu.vue";
import FooterEdu from "@/components/FooterEdu.vue";
// import HeaderEdu from "../components/HeaderEdu.vue";

export default {
  name: "HomeView",
  components: {
    // HelloWorld,
    HeaderEdu,
    HomeEdu,
    CounterEdu,
    AboutEdu,
    CoursesEdu,
    TeachersEdu,
    ReviewsEdu,
    ContactEdu,
    FooterEdu,
  },
};
</script>
