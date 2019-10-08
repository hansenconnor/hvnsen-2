<template>
  <div>
    <section class="lg bg-black">
      <div class="container">
        <a href="/"><img src="~/assets/images/logo.svg" class="mb-10 mt-2" alt="Hansen Logo"></a>
        <img src="~/assets/images/DesignAndDevelopment.svg" class="mb-4" style="width: 80vw;" alt="The Future of Design &amp; Development">
        <h1 class="mb-6 text-white font-bold">Digital Solutions</h1>
      </div>
    </section>
    
    <section class="flex bg-white lg">
      <div class="container">
        <div class="row">
          <h1 class="heading">If you can dream it...</h1>
          <h2 class="subhead">...We will build it</h2>
          <p>
            We are on a mission to redefine the design and development process
            from the ground up. 
          </p>
        </div>
      </div>
    </section>

    <section class="flex bg-gray-200 lg">
      <div class="container">
        <div class="row">
          <h1 class="heading">It starts as an idea</h1>
          <h2 class="subhead">And blossoms into reality</h2>
          <p>
            We are on a mission to redefine the design and development process
            from the ground up. 
          </p>
        </div>
      </div>
    </section>

    <section id="preFooter" class="flex lg" :style="{ backgroundImage: `url(${abstractBackground})` }">
      <div class="container">
        <div class="row">
          <h1 class="heading text-white">Ready?</h1>
          <h2 class="subhead text-white">Explore our recent projects or send us a message to begin.</h2>
          <h-button :text="'Hello World'" />
        </div>
      </div>
      <div class="flex">
        
      </div>
    </section>

  </div>
</template>

<script>
import abstractBackground from '~/assets/images/abstract-background.jpg'
import HButton from '~/components/buttons/PrimaryButton'

export default {
  data() {
    return {
      abstractBackground
    }
  },
  components: {
    HButton
  }
}
</script>

<style>
#preFooter {
  background-size: cover; 
  background-repeat: no-repeat;
  background-position: center center;
}
</style>
