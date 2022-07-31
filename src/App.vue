<template>
  <div>
    <nav class="navbar navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="@/assets/images/exclude.svg" alt="" width="30" height="24" class="d-inline-block align-text-top">
          PASOFT
        </a>
      </div>
    </nav>
  <MainTop/>
  <MailForm/>
 
  </div>
</template>

<script>
import MainTop from './components/MainTop.vue'
import MailForm from './components/MailForm.vue'

export default {
  name: 'App',
  components: {
    MainTop,MailForm
}
}
</script>

<style>

</style>
