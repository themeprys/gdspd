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
          <div class="card is-shadowless">
            <div class="card-image">
              <figure class="image is-2by1">
                <img
                  src="https://bulma.io/images/placeholders/1280x960.png"
                  alt="Placeholder image"
                />
              </figure>
            </div>
            <h4>Video Nestle</h4>
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
            <h4>Video Campina</h4>            
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
            <h4>Video Nestle</h4>            
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
            <h4>Video Campina</h4>            
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
            <h4>Video Nestle</h4>            
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
            <h4>Video Campina</h4>            
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
            <h4>Video Nestle</h4>            
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
            <h4>Video Nestle</h4>            
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
        indicator: false,
        arrowHover: false,      
        repeat: true,  
        autoplay: true,
        arrow: false,
        pauseHover: false,
        pauseInfo: false
        };
  },
};
</script>