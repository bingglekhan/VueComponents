<template>
    <div class="animated"
        v-show="active">
        <slot/>
    </div>

</template>

<script>

export default {
    name: 'AliveTab',

    props: {
        active: {
            type: Boolean,
            default: false,
        },
    },
};

</script>
