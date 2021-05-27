<template>
  <div>
    <login-form />
    <sign-up 
      @click="show_signup"
      style="display: none;" />
    <log-out style="display: none;" />
  </div>
</template>

<script>

export default {
  name: 'PageIndex',
  components: { 
    'login-form': require('components/Loginform.vue').default,
    'sign-up': require('components/Signup.vue').default,
    'log-out': require('components/Logout.vue').default
  },
  methods: {
    show_signup(){
       
    }
  }
}
</script>
