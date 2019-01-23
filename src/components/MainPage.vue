<template>
  <div  class="content">
    <div class="vertical-center">
      <strong>
      <div class="display-3">Redditaisai</div>
      <p class="lead">Online Touhou doujin convention</p>
      </strong>
      <b-btn variant="info" href="https://www.reddit.com/r/touhou/comments/aiqxra/redditaisai_2019_information_and_signup/">More Info</b-btn>
      <b-btn variant="info" href="https://discord.gg/cbPSbqQ">Discord Server</b-btn>
      <b-btn variant="info" href="https://goo.gl/forms/wrCZ3ioBegNcm8PA3k">Participate</b-btn>
    </div>
    <b-container class="bottom-text">
      Image Credit: <a href="https://www.pixiv.net/member.php?id=230478">Freeze-Ex</a>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'Main',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style scoped>
.content {
  height: 100vh;
}

.bottom-text {
  position: absolute;
  color: white;
  bottom: 0;
}

.vertical-center {
  padding-top: 30px;
  padding-bottom: 30px;
  background-image: linear-gradient(to right,
    rgb(0,0,0,0),
    rgb(255, 255, 255, 0.75),
    rgb(255, 255, 255, 0.75),
    rgb(255, 255, 255, 0.75),
    rgb(0,0,0,0));
  position: relative;
  top: 50%;
}
</style>
