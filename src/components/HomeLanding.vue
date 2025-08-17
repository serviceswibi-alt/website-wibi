<script setup>
import Preloader from "./home-landing/Preloader.vue";
import Navbar from "./home-landing/Navbar.vue";
import Intro from "./home-landing/Intro.vue";
import About from "./home-landing/About.vue";
import Achievement from "./home-landing/Achievement.vue";
import Testimoni from "./home-landing/Testimoni.vue";
import Services from "./home-landing/Services.vue";
import Pricing from "./home-landing/Pricing.vue";
import Contact from "./home-landing/Contact.vue";
import FooterHome from "./home-landing/Footer.vue";
</script>

<template>
  <div style="padding: 0 2;">
        <!-- preloader -->
         <Preloader />
        <!-- navbar -->
		<Navbar />
		<!-- end navbar -->

        <!-- intro -->
		<Intro />
		<!-- end intro -->

        <!-- about -->
		<About />
		<!-- end about -->

        <!-- achievement -->
		<Achievement />	
		<!-- end achievement -->

        <!-- testimonial -->
		<Testimoni />
		<!-- end testimonial -->

        <!-- services -->
		<Services />
		<!-- end services -->

        <!-- pricing -->
		<Pricing />
		<!-- end pricing -->

        <!-- contact -->
		<Contact />
		<!-- end contact -->

        <!-- footer -->
		<FooterHome />
		<!-- end footer -->
    <!-- semua konten HTML copy-paste di sini -->
  </div>
</template>
