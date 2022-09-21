<template>
  <div class="gd_porfoliolist">
    <div class="columns has-text-centered is-multiline mt-5">

      <!-- 01 - Campina Gratis Ongkir -->

      <div class="column is-4">
        <b-modal v-model="modal1">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1liiv1g1JWim-zy1g_vgFtjdJBEm8RKJ4/preview"
              width="640"
              height="380"
              allow="autoplay"
            ></iframe>
          </div>
        </b-modal>
        <div class="card is-shadowless">
          <div class="card-image">
            <a
              label="Launch image modal"
              type="is-primary"
              size="is-medium"
              @click="modal1 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Campina Gratis Ongkir"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Campina</b></b-tag>

            </a>
          </div>
          <h4>Gratis Ongkir</h4>
        </div>
      </div>

      <!-- 02 - Campina x Xiaomi -->

      <div class="column is-4">
        <b-modal v-model="modal2">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1ZyMeIL6qW1nqa4YXxLiuG8FcEd_6misS/preview"
              width="640"
              height="380"
              allow="autoplay"
            ></iframe>
          </div>
        </b-modal>
        <div class="card is-shadowless">
          <div class="card-image">
            <a
              label="Launch image modal"
              type="is-primary"
              size="is-medium"
              @click="modal2 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Campina x Xiaomi"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Campina</b></b-tag>

            </a>
          </div>
          <h4>Campina x Xiaomi</h4>
        </div>
      </div>


      <!-- 03 - Nestle Episode 3 -->

      <div class="column is-4">
        <b-modal v-model="modal3">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1peCZnXcEkFXsb7dnXRAh4ndhROik0O-u/preview"
              width="640"
              height="380"
              allow="autoplay"
            ></iframe>
          </div>
        </b-modal>
        <div class="card is-shadowless">
          <div class="card-image">
            <a
              label="Launch image modal"
              type="is-primary"
              size="is-medium"
              @click="modal3 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Nestle Episode 3"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Nestle</b></b-tag>

            </a>
          </div>
          <h4>Episode 3</h4>
        </div>
      </div>

      <!-- 04 - Nestle Perfect Store Rating -->

      <div class="column is-4">
        <b-modal v-model="modal4">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1ej0QCTjgKgOZy5X-bz83EtwaEFX3C726/preview"
              width="640"
              height="380"
              allow="autoplay"
            ></iframe>
          </div>
        </b-modal>
        <div class="card is-shadowless">
          <div class="card-image">
            <a
              label="Launch image modal"
              type="is-primary"
              size="is-medium"
              @click="modal4 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Nestle Perfect Store Rating"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Nestle</b></b-tag>

            </a>
          </div>
          <h4>Perfect Store Rating</h4>
        </div>
      </div>

      <!-- 05 - BPJS Ketenagakerjaan -->

      <div class="column is-4">
        <b-modal v-model="modal5">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1ldFW7Nd5-_1IZDPs4xaSoEVNnISqS2A-/preview"
              width="640"
              height="380"
              allow="autoplay"
            ></iframe>
          </div>
        </b-modal>
        <div class="card is-shadowless">
          <div class="card-image">
            <a
              label="Launch image modal"
              type="is-primary"
              size="is-medium"
              @click="modal5 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="BPJS Ketenagakerjaan"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>BPJS</b></b-tag>

            </a>
          </div>
          <h4>BPJS Ketenagakerjaan</h4>
        </div>
      </div>

      <!-- 06 - Elnusa Transamudera -->

      <div class="column is-4">
        <b-modal v-model="modal6">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1bES0nlqbDpg3W9k27_hKlxnl90yn5pr0/preview"
              width="640"
              height="380"
              allow="autoplay"
            ></iframe>
          </div>
        </b-modal>
        <div class="card is-shadowless">
          <div class="card-image">
            <a
              label="Launch image modal"
              type="is-primary"
              size="is-medium"
              @click="modal6 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Elnusa Transamudera"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Elnusa</b></b-tag>

            </a>
          </div>
          <h4>Elnusa Transamudera</h4>
        </div>
      </div>

      <!-- 07 - Campina Let's Go Concerto -->

            <div class="column is-4">
        <b-modal v-model="modal7">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1raGh_rGnV6TBe9KceTSd-1iTv7YZhK-f/preview"
              width="640"
              height="380"
              allow="autoplay"
            ></iframe>
          </div>
        </b-modal>
        <div class="card is-shadowless">
          <div class="card-image">
            <a
              label="Launch image modal"
              type="is-primary"
              size="is-medium"
              @click="modal7 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Campina Let's Go Concerto"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Campina</b></b-tag>

            </a>
          </div>
          <h4>Let's Go Concerto</h4>
        </div>
      </div>

      <!-- 08 - Campina Counter -->

      <div class="column is-4">
        <b-modal v-model="modal8">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1iIgde5FSuSsKncssAiLNgXOg0VQhuqK6/preview"
              width="640"
              height="380"
              allow="autoplay"
            ></iframe>
          </div>
        </b-modal>
        <div class="card is-shadowless">
          <div class="card-image">
            <a
              label="Launch image modal"
              type="is-primary"
              size="is-medium"
              @click="modal8 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Campina Counter"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Campina</b></b-tag>

            </a>
          </div>
          <h4>Campina Counter</h4>
        </div>
      </div>
      



    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      modal1: false,
      modal2: false,
      modal3: false,
      modal4: false,
      modal5: false,
      modal6: false,
      modal7: false,
      modal8: false, 
    };
  },
};
</script>