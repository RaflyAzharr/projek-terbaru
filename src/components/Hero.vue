<template>
  <div class="hero">
    <!-- Desktop -->
    <div class="d-none d-md-block">
      <div class="row mt-4">
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Selamat Datang di Website Resmi</strong>
                <br />RA ASY SYIFA
              </h2>
              <p>ayo daftarkan segera</p>
              <router-link class="btn btn-lg btn-primary" to="/daftar">
                <b-icon-arrow-right></b-icon-arrow-right>Daftar Sekarang
              </router-link>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div>
  <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="480"
  >
    <b-carousel-slide
      caption=""
      img-src="https://scontent.fcgk13-1.fna.fbcdn.net/v/t1.6435-9/67313738_161480958317472_4205081352845918208_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=8bfeb9&_nc_eui2=AeFv2PtdT2gau1T-xQ4yJnqvTmg738M-0s5OaDvfwz7SziByOxdpSma3-AxOc5i1cSHwHqVIi6UXX3tRV9y4JgIe&_nc_ohc=m9_m7bJFy3YAX-lcYOX&_nc_ht=scontent.fcgk13-1.fna&oh=00_AfAhiGzu-0W5_uEGiBHXBJS-2nrIK97Gryh-N9N9jLfSdQ&oe=64374761"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="https://scontent.fcgk13-1.fna.fbcdn.net/v/t1.6435-9/64679346_154447232354178_29709225089302528_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=8bfeb9&_nc_eui2=AeEJb8eM8OQJ2_cyFpPJXQ-IHe0kAN92Lkkd7SQA33YuSQdNmMHDgkRiJBJYi6_WcetGaLlx7niVTdsdpkTUcpkR&_nc_ohc=-rnnnDO_JGkAX_bPdBw&_nc_ht=scontent.fcgk13-1.fna&oh=00_AfCgdvj1dt5DgR-z0tgQA-jUiDqHPntlQT2wkzwkkdyKFA&oe=64376FD7"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="https://scontent.fcgk13-1.fna.fbcdn.net/v/t1.6435-9/51026306_101033047695597_5299544882220630016_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeHcGBn11gKRE4dxx6enFZkGDwpAl85uW6sPCkCXzm5bq2G_U9bcjNRKYWVQxG1xILwImcC6sdkA1gi0qt8gSARW&_nc_ohc=Vv9jkslui7wAX-aUU_u&_nc_ht=scontent.fcgk13-1.fna&oh=00_AfBMgFDdHs6xyr4ODNndXf0VLbBwm69Ow6c8ARF0l1aVxw&oe=64376543"
    ></b-carousel-slide>
  </b-carousel>
</div>
        </div>
      </div>
    </div>

    <!-- Mobile -->
    <div class="d-sm-block d-md-none">
      <div class="row mt-4">
        <div class="col-md-6 mb-3">
          <div>
  <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="480"
  >
    <b-carousel-slide
      caption=""
      img-src="https://scontent.fcgk13-1.fna.fbcdn.net/v/t1.6435-9/67313738_161480958317472_4205081352845918208_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=8bfeb9&_nc_eui2=AeFv2PtdT2gau1T-xQ4yJnqvTmg738M-0s5OaDvfwz7SziByOxdpSma3-AxOc5i1cSHwHqVIi6UXX3tRV9y4JgIe&_nc_ohc=m9_m7bJFy3YAX-lcYOX&_nc_ht=scontent.fcgk13-1.fna&oh=00_AfAhiGzu-0W5_uEGiBHXBJS-2nrIK97Gryh-N9N9jLfSdQ&oe=64374761"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="https://scontent.fcgk13-1.fna.fbcdn.net/v/t1.6435-9/64679346_154447232354178_29709225089302528_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=8bfeb9&_nc_eui2=AeEJb8eM8OQJ2_cyFpPJXQ-IHe0kAN92Lkkd7SQA33YuSQdNmMHDgkRiJBJYi6_WcetGaLlx7niVTdsdpkTUcpkR&_nc_ohc=-rnnnDO_JGkAX_bPdBw&_nc_ht=scontent.fcgk13-1.fna&oh=00_AfCgdvj1dt5DgR-z0tgQA-jUiDqHPntlQT2wkzwkkdyKFA&oe=64376FD7"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Third Slide"
      img-src="https://scontent.fcgk13-1.fna.fbcdn.net/v/t1.6435-9/51026306_101033047695597_5299544882220630016_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeHcGBn11gKRE4dxx6enFZkGDwpAl85uW6sPCkCXzm5bq2G_U9bcjNRKYWVQxG1xILwImcC6sdkA1gi0qt8gSARW&_nc_ohc=Vv9jkslui7wAX-aUU_u&_nc_ht=scontent.fcgk13-1.fna&oh=00_AfBMgFDdHs6xyr4ODNndXf0VLbBwm69Ow6c8ARF0l1aVxw&oe=64376543"
    ></b-carousel-slide>
  </b-carousel>
</div>
        </div>
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Selamat Datang di Website Resmi</strong>
                <br />RA ASY SYIFA
              </h2>
              <p>ayo daftarkan segera</p>
              <router-link class="btn btn-lg btn-primary" to="/daftar">
                <b-icon-arrow-right></b-icon-arrow-right>Daftar Sekarang
              </router-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
body {
  background-image: url('../assets/images/backround\ tk.jpg');
}
</style>