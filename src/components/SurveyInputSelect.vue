<template lang="pug">
include SurveyInputSelect.pug
</template>

<script>
import SurveyInputBase from "./SurveyInputBase.vue"

export default {
  extends: SurveyInputBase,
  props: ['options']
}
</script>