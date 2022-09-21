<template>
    <section>
        <b-tabs 
        v-model="activeTab" 
        position="is-centered" 
        class="block"
          type="is-toggle is-toggle-rounded"
          multiline

        >
            <b-tab-item label="Motion Graphic">
                <HomeMotionList />
            </b-tab-item>

            <b-tab-item label="Video Event">
                <HomeVideoList />
            </b-tab-item>

        </b-tabs>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                activeTab: 0,
            }
        }
    }
</script>