<template>
  <b-carousel
    :indicator="indicator"
    :arrow-hover="arrowHover"
    :repeat="repeat"
    :autoplay="autoplay"
    :arrow="arrow"
    :pause-hover="pauseHover"
    :pause-info="pauseInfo"
    class="pt-6"
  >
    <b-carousel-item class="gd_porfoliolist">
      <div class="columns has-text-centered">
        <div class="column">
          <b-modal v-model="modal1">
            <iframe
              src="https://drive.google.com/file/d/1liiv1g1JWim-zy1g_vgFtjdJBEm8RKJ4/preview"
              width="640"
              height="380"
              allow="autoplay"
            ></iframe>
          </b-modal>
          <b-modal v-model="modal2">
            <iframe
              src="https://drive.google.com/file/d/1ZyMeIL6qW1nqa4YXxLiuG8FcEd_6misS/preview"
              width="640"
              height="380"
              allow="autoplay"
            ></iframe>
          </b-modal>
          <div class="card is-shadowless">
            <div class="card-image">
              <a
                label="Launch image modal"
                type="is-primary"
                size="is-medium"
                @click="modal1 = true"
              >
                <figure class="image is-2by1">
                  <img
                    src="https://bulma.io/images/placeholders/1280x960.png"
                    alt="Campina Gratis Ongkir"
                  />
                </figure>
              </a>
            </div>
            <h4>Campina Gratis Ongkir</h4>
          </div>
        </div>
        <div class="column">
          <div class="card is-shadowless">
            <div class="card-image">
              <a
                label="Launch image modal"
                type="is-primary"
                size="is-medium"
                @click="modal2 = true"
              >
                <figure class="image is-2by1">
                  <img
                    src="https://bulma.io/images/placeholders/1280x960.png"
                    alt="Placeholder image"
                  />
                </figure>
              </a>
            </div>
            <h4>Campina x Xiaomi</h4>
          </div>
        </div>
      </div>
      <div class="columns has-text-centered">
        <div class="column">
          <div class="card is-shadowless">
            <div class="card-image">
              <figure class="image is-2by1">
                <img
                  src="https://bulma.io/images/placeholders/1280x960.png"
                  alt="Placeholder image"
                />
              </figure>
            </div>
            <h4>Motion Graphic Nestle</h4>
          </div>
        </div>
        <div class="column">
          <div class="card is-shadowless">
            <div class="card-image">
              <figure class="image is-2by1">
                <img
                  src="https://bulma.io/images/placeholders/1280x960.png"
                  alt="Placeholder image"
                />
              </figure>
            </div>
            <h4>Motion Graphic Campina</h4>
          </div>
        </div>
      </div>
    </b-carousel-item>
    <b-carousel-item class="gd_porfoliolist">
      <div class="columns has-text-centered">
        <div class="column">
          <div class="card is-shadowless">
            <div class="card-image">
              <figure class="image is-2by1">
                <img
                  src="https://bulma.io/images/placeholders/1280x960.png"
                  alt="Placeholder image"
                />
              </figure>
            </div>
            <h4>Motion Graphic Nestle</h4>
          </div>
        </div>
        <div class="column">
          <div class="card is-shadowless">
            <div class="card-image">
              <figure class="image is-2by1">
                <img
                  src="https://bulma.io/images/placeholders/1280x960.png"
                  alt="Placeholder image"
                />
              </figure>
            </div>
            <h4>Motion Graphic Campina</h4>
          </div>
        </div>
      </div>
      <div class="columns has-text-centered">
        <div class="column">
          <div class="card is-shadowless">
            <div class="card-image">
              <figure class="image is-2by1">
                <img
                  src="https://bulma.io/images/placeholders/1280x960.png"
                  alt="Placeholder image"
                />
              </figure>
            </div>
            <h4>Motion Graphic Nestle</h4>
          </div>
        </div>
        <div class="column">
          <div class="card is-shadowless">
            <div class="card-image">
              <figure class="image is-2by1">
                <img
                  src="https://bulma.io/images/placeholders/1280x960.png"
                  alt="Placeholder image"
                />
              </figure>
            </div>
            <h4>Motion Graphic Nestle</h4>
          </div>
        </div>
      </div>
    </b-carousel-item>
  </b-carousel>
</template>

<script>
export default {
  data() {
    return {
      modal1: false,
      modal2: false,
      indicator: false,
      arrowHover: false,
      repeat: true,
      autoplay: false,
      arrow: false,
      pauseHover: false,
      pauseInfo: false,
    };
  },
};
</script>