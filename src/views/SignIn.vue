<template>
  <AuthForm title="Sign in to your account" :isSignIn="true" />
</template>

<script>
import AuthForm from "../components/AuthForm.vue";

export default {
  name: "SignIn",
  components: {
    AuthForm,
  },
};
</script>
