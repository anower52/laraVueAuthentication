<template>
    <div class="container">
    <div class="card text-center">
  <div class="card-header">
    {{ app.user ? app.user.name: 'HOME'}}
  </div>
  <div class="card-body">
    <h5 class="card-title">{{ app.user ? app.user.username: 'About Home'}}</h5>
    <p class="card-text">{{ app.user ? app.user.created_at: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industrys standard dummy text ever since the 1500s'}}</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
  <div class="card-footer text-muted">
    2 days ago
  </div>
</div> 
    </div>
</template>

<script>
    export default {
        name: 'navbar',
        props: ['app'],
        data(){
            return {

            }
        },
    };
</script>

<style lang="scss" scoped>

</style>