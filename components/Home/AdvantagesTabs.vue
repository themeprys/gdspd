<template>
  <div class="columns mb-6 gd_advantagestabcustom">
    <div class="column is-10 is-offset-1">
      <section>
        <b-tabs
          v-model="activeTab"
          type="is-toggle is-toggle-rounded"
          position="is-centered"
          class="block"
          multiline
        >
          <b-tab-item label="Projects With Creative Ideas" icon="lightbulb">
            <HomeProjectsWithCreativeIdeas />
          </b-tab-item>

          <b-tab-item label="Provide Best Quality" icon="thumb-up">
            <HomeProvideBestQuality />
          </b-tab-item>
          <b-tab-item label="Work on Time" icon="clock-time-four">
            <HomeWorkonTime />
          </b-tab-item>

          <b-tab-item label="Projects with Creative Ideas" icon="comment-multiple">
            <HomeProjectswithCreativeIdea />
          </b-tab-item>
        </b-tabs>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      activeTab: 0,
    };
  },
};
</script>
