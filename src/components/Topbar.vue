<template>
<div class="topbar">
    <h1>CV Portal</h1>
    <NavMenu/>       
</div>
</template>

<script>
import { mapState, mapActions, mapMutations } from 'vuex'
import NavMenu from './NavMenu.vue'

export default {
    name: 'Topbar',
    components: {NavMenu},
    data() { return {}},
    computed:{},
    methods: {}
}

</script>

<style scoped>

.topbar {
    background-color: var(--topbar-bg-color);
    /* height: 150px; */
    margin-bottom: 10px;
    text-align: center;
}

h1{ 
    padding: 10px;
    margin: 0px;
    font-size: 48px;
}
</style>