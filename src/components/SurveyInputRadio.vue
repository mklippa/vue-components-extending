<template lang="pug">
include SurveyInputRadio.pug
</template>

<script>
import SurveyInputBase from "./SurveyInputBase.vue"

export default {
  extends: SurveyInputBase,
  props: ['options', 'name']
}
</script>