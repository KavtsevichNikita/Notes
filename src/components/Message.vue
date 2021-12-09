<template>
<div class="message">
  <p>  {{message}}</p>
  </div>
</template>

<script>
export default {
    props:{
        message:{
            type: String,
            // required: true
            default: "def message"
        }
    }
}
</script>

