<script>
  import Navbar from "./Components/_Layout/Navbar.svelte";
  import Banner from "./Components/_Layout/Banner.svelte";
  import Services from "./Components/Services/Services.svelte";
  import About from "./Components/About/About.svelte";
  import Testimonials from "./Components/Testimonials/Testimonials.svelte";
  import Social from "./Components/Social/Social.svelte";
  import Footer from "./Components/_Layout/Footer.svelte";
  import DATA from "./Data/data";
</script>

<!-- <script>
  import Link from "./Link.svelte";
  import Route from "./Route.svelte";
</script> -->

<!-- Navigation goes here -->
<!-- <Link page={{ path: '/', name: 'Home' }} />
<Link page={{ path: '/about', name: 'About' }} /> -->

<!-- Main container goes here -->
<!-- <Route /> -->
<!-- Navbar -->
<Navbar navlists={DATA.NAVBAR_DATA} header={DATA.HEADER} />
<!-- Banner -->
<Banner bannerData={DATA.BANNER_DATA} } />
<!-- Services -->
<Services serviceData={DATA.SERVICE_DATA} />
<!-- About -->
<About aboutData={DATA.ABOUT_DATA} />
<!-- Testimonials -->
<Testimonials testimonialData={DATA.TESTIMONIAL_DATA} />
<!-- Social Media -->
<Social socialData={DATA.SOCIAL_DATA} />
<!-- Footer -->
<Footer footerData={DATA.FOOTER_DATA} header={DATA.HEADER} />
