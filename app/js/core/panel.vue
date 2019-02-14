<template>
    <section class="panel">
        <h4>-{{title}}-</h4>
        <slot/>
    </section>
</template>

<script>
export default {
    name: 'Panel',
    props: {
        title: {
            type: String,
            default: "",
        },
    },
}
</script>

<style lang="scss">
    @import "../../css/element.scss";

    .panel {
        @include panel;
    }
</style>
