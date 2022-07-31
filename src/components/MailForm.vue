<template>
  <div>
    <form ref="form" @submit.prevent="sendEmail">
      <label>Name</label>
      <input type="text" name="user_name">
      <label>Email</label>
      <input type="email" name="user_email">
      <label>Message</label>
      <textarea name="message"></textarea>
      <input type="submit" value="Send">
    </form>
  </div>  
</template>
<script>
import emailjs from '@emailjs/browser';

export default {
     name: 'MailForm',
     methods: {
    sendEmail() {
      emailjs.sendForm('service_bvnamyk', 'template_tenwpgd', this.$refs.form, 'udZxz8W6B070C3u3a')
        .then((result) => {
            console.log('SUCCESS!', result.text);
        }, (error) => {
            console.log('FAILED...', error.text);
        });
    }
  }

}
</script>