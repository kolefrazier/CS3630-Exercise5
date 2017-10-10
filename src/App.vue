<template>
    <div class="container">
        <app-header></app-header>
        <hr>
        <div class="row">
            <app-server-list></app-server-list>
            <app-server-details></app-server-details>
        </div>
        <hr>
        <app-footer></app-footer>
    </div>
</template>

<script>
    import Header from './Header.vue';
    import Footer from './Footer.vue';
    import ServerList from './ServerList.vue';
    import ServerDetails from './ServerDetails.vue';

    export default {
        components: {
            'app-header': Header,
            'app-footer': Footer,
            'app-server-list': ServerList,
            'server-details': ServerDetails
        }
    }
</script>

<style>

</style>
