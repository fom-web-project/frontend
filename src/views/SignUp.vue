<template>
  <AuthForm title="Sign up" :isSignIn="false" />
</template>

<script>
import AuthForm from "../components/AuthForm.vue";

export default {
  name: "SignUp",
  components: {
    AuthForm,
  },
};
</script>
