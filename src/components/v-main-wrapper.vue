<template>
    <div class="v-main-wrapper">
        <p>header</p>
        <v-calendar />
    </div>
</template>

<script>
import vCalendar from './v-calendar'

export default {
    name: "v-main-wrapper",
    components: {
        vCalendar
    },
    props: {},
    data() {
        return {
            
        }
    },
    
}
</script>

<style lang="">
    
</style>