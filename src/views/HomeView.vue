<script setup>
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'
import HeroSection from '@/components/HeroSection.vue';
import AboutUs from '@/components/AboutUs.vue';
import WhyChooseUs from '@/components/WhyChooseUs.vue';
import Gallery from '@/components/Gallery.vue';
import PricingPlans from '@/components/PricingPlans.vue';
import HowItWorks from '@/components/HowItWorks.vue';
import FAQS from '@/components/FAQS.vue';
import ContactUs from '@/components/ContactUs.vue';
</script>

<template>
  <Navbar />
  <HeroSection />
  <AboutUs />
  <WhyChooseUs />
  <PricingPlans />
  <Gallery />
  <HowItWorks />
  <FAQS />
  <ContactUs />
  <Footer />
</template>
