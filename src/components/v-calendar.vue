<template>
    <div class="v-calendar">
        <h1>calendar</h1>
        <v-meeting />
    </div>
</template>

<script>
import vMeeting from './v-meeting'

export default {
    name: "v-calendar",
    components: {
        vMeeting
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