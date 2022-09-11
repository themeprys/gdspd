<template>
    <b-carousel-list v-model="test" :data="items" :items-to-show="4" class="is-shadowless">
        <template #item="list">
            <div class="card is-shadowless px-3">
                <div class="card-image">
                    <figure>
                        <img src="~/static/icon/icon_services.svg" width="80px" class="gd_ourservicesicon">
                    </figure>
                </div>
                <div class="card-content gd_ourserviceswrap">
                    <div class="content">
                        <p class="title is-6">{{ list.title }}</p>
                        <!-- <p class="subtitle is-7">{{ list.desc }}</p> -->
                    </div>
                </div>
            </div>
        </template>
    </b-carousel-list>
</template>

<script>
export default {
    data() {
        return {
            test: 0,
            items: [
                {
                    title: 'Company Profile',
                    desc: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt harum quasi voluptatem',
                },
                {
                    title: 'Explainer Video',
                    desc: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt harum quasi voluptatem',
                },
                {
                    title: 'Tutorial Video',
                    desc: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt harum quasi voluptatem',
                },
                {
                    title: 'Testimoni Video',
                    desc: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt harum quasi voluptatem',
                },
                {
                    title: 'Company Profile',
                    desc: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt harum quasi voluptatem',
                },
                {
                    title: 'Explainer Video',
                    desc: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt harum quasi voluptatem',
                },
                {
                    title: 'Tutorial Video',
                    desc: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt harum quasi voluptatem',
                },
                {
                    title: 'Testimoni Video',
                    desc: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt harum quasi voluptatem',
                },                
            ]
        }
    },
    methods: {
        info(value) {
            this.test = value
        }
    }
}
</script>