<template>
    <div class="btn">
        <slot/>
    </div>
</template>

<script>
export default {
    name: 'btn',
}
</script>

<style lang="scss">
    @import "../../css/element";

    .btn {
        @include btn;
    }
</style>
