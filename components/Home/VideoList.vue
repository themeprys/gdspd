<template>
  <div class="gd_porfoliolist">
    <div class="columns has-text-centered is-multiline mt-5">

      <!-- 01 - Nestle - Commitment -->

      <div class="column is-4">
        <b-modal v-model="modalvideoevent1">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1MuMw17b2ZryypEvpHxTrT6Fx1YTbM8R8/preview"
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
              @click="modalvideoevent1 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Nestle - Commitment"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Nestle</b></b-tag>

            </a>
          </div>
          <h4>Commitment</h4>
        </div>
      </div>

      <!-- 02 - Bukalapak - BukaTalks -->
      
      <div class="column is-4">
        <b-modal v-model="modalvideoevent2">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/19RNvD8eRxqgVeErcV3HfqpkZ83U0NaNO/preview"
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
              @click="modalvideoevent2 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Bukalapak - BukaTalks"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Bukalapak</b></b-tag>

            </a>
          </div>
          <h4>Bukalapak - BukaTalks</h4>
        </div>
      </div>

      <!-- 03 - Civic -->

      <div class="column is-4">
        <b-modal v-model="modalvideoevent3">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1wSv-dZwVABzysZUgQDpiErddLHWYLvaz/preview"
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
              @click="modalvideoevent3 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Civic"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Civic</b></b-tag>

            </a>
          </div>
          <h4>Civic - Highlights</h4>
        </div>
      </div>

      <!-- 04 - Prakerja -->

      <div class="column is-4">
        <b-modal v-model="modalvideoevent4">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1JKWeHsWboqGMzQcUxHeQyhFnwdQr6Mbt/preview"
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
              @click="modalvideoevent4 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Prakerja"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Prakerja</b></b-tag>

            </a>
          </div>
          <h4>Prakerja Highlights</h4>
        </div>
      </div>

      <!-- 05 - Federal - 2 Years Anniversary -->

      <div class="column is-4">
        <b-modal v-model="modalvideoevent5">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1JKNnsEntSXWuPJcwr15Y6MkdFIhIarou/preview"
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
              @click="modalvideoevent5 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Federal - 2 Years Anniversary"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Federal</b></b-tag>

            </a>
          </div>
          <h4>2 Years Anniversary</h4>
        </div>
      </div>

      <!-- 06 - KBN  -->

      <div class="column is-4">
        <b-modal v-model="modalvideoevent6">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1m_3k8D6cd16ozlZLyn6PgVdUY2dJgO2K/preview"
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
              @click="modalvideoevent6 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="KBN"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>KBN</b></b-tag>

            </a>
          </div>
          <h4>KBN Highlights</h4>
        </div>
      </div>      
      <!-- 07 - Nestle - Kudo Distribution Partnership -->

      <div class="column is-4">
        <b-modal v-model="modalvideoevent7">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1FR8PM2bVCt70UHuU2vlGY6cvOFLyyxm7/preview"
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
              @click="modalvideoevent7 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Nestle - Kudo Distribution Partnership"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Nestle</b></b-tag>

            </a>
          </div>
          <h4>Kudo Distribution Partnership</h4>
        </div>
      </div>      
      <!-- 08 - Puti Folon -->
      <div class="column is-4">
        <b-modal v-model="modalvideoevent8">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1z1yEt3yb_9YfLAhHj3HUO8iJL-PWMbXX/preview"
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
              @click="modalvideoevent8 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Puti Folon"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Puti Folon</b></b-tag>

            </a>
          </div>
          <h4>Puti Folon Highlights</h4>
        </div>
      </div>      
      <!-- 09 - Ruti Surui -->
      <div class="column is-4">
        <b-modal v-model="modalvideoevent9">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1fhk39m6UDlOBf1rh8hfaurWV--i1UN4I/preview"
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
              @click="modalvideoevent9 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Ruti Surui"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Ruti Surui</b></b-tag>

            </a>
          </div>
          <h4>Ruti Surui Highlights</h4>
        </div>
      </div>      
      <!-- 10 - Freeport - Tembagapura -->
      <div class="column is-4">
        <b-modal v-model="modalvideoevent10">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1RzzKrglg5ye7-aRDmSIDUHJz-oRurYPP/preview"
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
              @click="modalvideoevent10 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Freeport - Tembagapura"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Freeport</b></b-tag>

            </a>
          </div>
          <h4>Tembagapura</h4>
        </div>
      </div>      
      <!-- 11 - Trimina - Unboxing dan Cara Penggunaan -->
      <div class="column is-4">
        <b-modal v-model="modalvideoevent11">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1btQTSikZ944bmdUy96TgCTI2pui1ZTZ8/preview"
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
              @click="modalvideoevent11 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Trimina - Unboxing dan Cara Penggunaan"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Trimina</b></b-tag>

            </a>
          </div>
          <h4>Unboxing dan Cara Penggunaan</h4>
        </div>
      </div>      
      <!-- 12 - Trimina - Indonesia Hospital Expo -->
      <div class="column is-4">
        <b-modal v-model="modalvideoevent12">
          <div class="embed-container">
            <iframe
              src="https://drive.google.com/file/d/1J9IQAy0P0EREoWTnZ4NN06EueTUmsGDh/preview"
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
              @click="modalvideoevent12 = true"
            >
              <figure class="image is-16by9">
                <img
                  src="@/static/img/portothumbnail.webp"
                  alt="Trimina - Indonesia Hospital Expo"
                />
              </figure>
              <b-tag type="is-danger" rounded style="position: absolute; top: 0;left:0;margin: 10px 0 0 10px"><b>Trimina</b></b-tag>

            </a>
          </div>
          <h4>Indonesia Hospital Expo</h4>
        </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      modalvideoevent1: false,
      modalvideoevent2: false,
      modalvideoevent3: false,
      modalvideoevent4: false,
      modalvideoevent5: false,
      modalvideoevent6: false,
      modalvideoevent7: false,
      modalvideoevent8: false,
      modalvideoevent9: false,
      modalvideoevent10: false,
      modalvideoevent11: false,
      modalvideoevent12: false,                                                                  
    };
  },
};
</script>