<template>
    <div>
        <PostView :data="data[i]" v-for="(a, i) in data" :key="i" />
</div>
</template>

<script>
import PostView from "./PostView"


export default {
    name: "ContainerView",
    data() {
        return {

        }
    },
    components: {
        PostView,
    },
    props: {
        data: Array,

    },

}
</script>

<style></style>