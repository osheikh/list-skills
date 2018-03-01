<template>
  <div class='about'>
    <h1>Hello {{their_name}},This is an about page</h1>
    <p>Non dolor perferendis. Doloremque perferendis aut delectus dolor ipsum sunt. Enim harum aut et. Autem ex aut fugiat et et impedit non quod neque. Saepe quia qui.</p>
  </div>
</template>
<script>
  export default {
  name: 'Skills',
  data () {
    return {
      their_name:this.$route.params.name
    }
  }
}
</script>