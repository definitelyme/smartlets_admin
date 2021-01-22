<template>
    <div>
        <dropdown>Home</dropdown>
        <secondary-button>tis is a button</secondary-button>
    </div>
</template>

<script>
import Dropdown from '../../Jetstream/Dropdown.vue'
import SecondaryButton from '../../Jetstream/SecondaryButton.vue'
export default {
  components: { SecondaryButton, Dropdown },
    data() {
        return {
            //
        }
    },
}
</script>
