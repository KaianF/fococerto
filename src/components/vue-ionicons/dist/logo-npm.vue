<template>
  <div
    class="ion"
    :class="ionClass"
    :title="iconTitle"
    name="logo-npm-icon">
    <svg :width="w" :height="h" class="ion__svg" id="Layer_1" viewBox="0 0 512 512"><path class="st0" d="M227.6 213.1H256v57.1h-28.4z"/><path class="st0" d="M0 156v171.4h142.2V356H256v-28.6h256V156H0zm142.2 142.9h-28.4v-85.7H85.3v85.7H28.4V184.6h113.8v114.3zm142.2 0h-56.9v28.6h-56.9V184.6h113.8v114.3zm199.2 0h-28.4v-85.7h-28.4v85.7h-28.4v-85.7H370v85.7h-56.9V184.6h170.7v114.3z"/></svg>
  </div>
</template>

<script>
import IoniconsMixin from './ionicons-mixin'

export default {
  name: "logo-npm-icon",
  mixins: [
    IoniconsMixin
  ],
  data () {
    let iconTitle = this.title ? this.title : "Logo Npm Icon"
    return {
      iconTitle: iconTitle
    }
  }
}
</script>

