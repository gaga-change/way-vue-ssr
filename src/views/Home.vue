<template>
    <div>
        {{a}}
    </div>
</template>
<script>
export default {
    data () {
        return {
            a: 'gaga'
        }
    },
    methods: {
        title () {
            return this.item.title
        }
    }
}
</script>

