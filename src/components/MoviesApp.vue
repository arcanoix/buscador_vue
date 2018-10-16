<template>
    <div>
        <h1 class="text-center text-muted">Buscador Con Vuex</h1>
        <search-form></search-form>
        <hr>
        <movie-list></movie-list>
    </div>
</template>


<script>

    import SearchForm from './SearchForm.vue'
    import MovieList from './MovieList.vue';

export default {
    components:{
        SearchForm,
        MovieList
    }
}
</script>

