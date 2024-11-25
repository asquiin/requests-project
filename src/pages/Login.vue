<script setup></script>

<template>
  <div class="login-page w-full h-screen bg-red justify-center align-center">
    <v-card variant="flat" color="white" width="400px" class="rounded-lg">
      <v-col>
      <v-list-item class="mb-0 pb-0" :style="{color: '#50B053'}"> Логин или Телефон </v-list-item>
        <v-text-field placeholder="Телефон" variant="underlined" />
        <v-text-field placeholder="Пароль" variant="underlined" />
        <v-card-actions class="flex justify-center">
          <v-btn
            text="Войти"
            width="110px"
            height="36px"
            variant="flat"
            color="#50B053"
          />
        </v-card-actions>
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
