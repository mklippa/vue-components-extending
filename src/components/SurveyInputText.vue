<template lang="pug">
include SurveyInputText.pug
</template>

<script>
import SurveyInputBase from "./SurveyInputBase.vue"

export default {
  extends: SurveyInputBase,
  props: ['placeholder']
}
</script>