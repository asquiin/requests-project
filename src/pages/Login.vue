<script setup></script>

<template>
  <div class="login-page w-full h-screen bg-red justify-center align-center">
    <v-card variant="flat" color="white" width="400px">
      <v-col>
        <v-text-field placeholder="Телефон" variant="underlined" />
        <v-text-field placeholder="Пароль" variant="underlined" />
      </v-col>
    </v-card>
  </div>
</template>

<style lang="scss" scoped>
.login-page {
  background: url("src/assets/authpic.jpeg") no-repeat center center;
  background-size: cover;
  display: flex;
}
</style>
