<!-- <template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template> -->

<template>
  <div>
    
    <Header />
    <HeroSection />
    <FeaturedCourses />
    <NewArrivals />
    <FeaturedInstructors />
    <StudentReviews />
    <Blog />
    <FAQ />
    <Footer />
  </div>
</template>

<script setup>
import Header from '~/components/Header.vue'
import HeroSection from '~/components/HeroSection.vue'
import FeaturedCourses from '~/components/FeaturedCourses.vue'
import NewArrivals from '~/components/NewArrivals.vue'
import FeaturedInstructors from '~/components/FeaturedInstructors.vue'
import StudentReviews from '~/components/StudentReviews.vue'
import Blog from '~/components/Blog.vue'
import FAQ from '~/components/FAQ.vue'
import Footer from '~/components/Footer.vue'
</script>
