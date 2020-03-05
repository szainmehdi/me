<template>
  <v-app>
    <v-content>
      <v-container fluid
                   class="fill-height text-center d-flex flex-column justify-center align-center"
      >
        <v-avatar color="white" size="96">
          <img src="./assets/profile.jpg">
        </v-avatar>
        <h1 class="display-2 mt-12">Hi, I'm Zain!</h1>
        <p class="title mt-8">Software Engineer at Square, Inc.</p>
        <div class="links mt-6">
          <v-btn large href="https://github.com/szainmehdi/" target="_blank" class="mr-6">
            <v-icon left>mdi-github-circle</v-icon> Github
          </v-btn>
          <v-btn large href="https://linkedin.com/in/szainmehdi/" target="_blank">
            <v-icon left>mdi-linkedin</v-icon> LinkedIn
          </v-btn>
        </div>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css?family=Spartan:100,200,300,400,500,600,700,800,900&display=swap');

.display-2 {
}
</style>
