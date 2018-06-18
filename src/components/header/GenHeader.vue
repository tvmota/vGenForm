<script>
import FontAwesomeIcon from '@fortawesome/vue-fontawesome'
import faFileAlt from '@fortawesome/fontawesome-free-solid/faFileAlt'

export default {
  name: 'app-header',
  components: {
    FontAwesomeIcon
  },
  computed: {
    icon () {
      return faFileAlt
    }
  }
}
</script>
<template>
  <div class="navbar bg-secondary p-2">
    <section class="navbar-section">
      <a class="navbar-brand mr-2">
        <h3><font-awesome-icon :icon="icon"></font-awesome-icon></h3>
      </a>
      <h3 class="text-primary">vFormGen</h3>
    </section>
  </div>
</template>
