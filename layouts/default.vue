<template>
  <div>
    <nuxt />
    <footer>
      <section class="bg-black m-0 p-0 pb-2">
        <div class="flex bg-white py-4 mx-2 justify-center">
            <div class="footer-social-links">
              <a href="#!" class="facebook-link text-black p-1"><i class="fa fa-facebook"></i></a>
              <a href="#!" class="twitter-link text-black p-1"><i class="fa fa-twitter"></i></a>
              <a href="#!" class="instagram-link text-black p-1"><i class="fa fa-instagram"></i></a>
              <a href="#!" class="dribbble-link text-black p-1"><i class="fa fa-dribbble"></i></a>
              <a href="#!" class="github-link text-black p-1"><i class="fa fa-github"></i></a>
            </div>
        </div>
        <div class="flex bg-gray-300 p-2 mx-2">
          hvnsen
        </div>
      </section>
    </footer>
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
