<template>
    <div>
        <h1>Add Movie</h1>
        <MovieForm />
    </div>
</template>


<script>
import MovieForm from "@/components/MovieForm.vue";

export default {
  components: {
    MovieForm // Registering MovieForm component
  }
};
</script>
