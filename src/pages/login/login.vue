<script lang="ts" setup>
const router = useRouter()

function login() {
  router.push('/index')
  api.login({ password: '123', username: '12' })
}
</script>

<template>
  <div h-100vh w-100vw flex items-center justify-center>
    <div btn @click="login">
      登陆
    </div>
  </div>
</template>

<style>

</style>
