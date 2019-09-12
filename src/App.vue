<template>
  <div id="app">
    <img
      alt="Vue logo"
      src="./assets/logo.png"
    >
    <survey-input-text
      question="1. What is your name?"
      placeholder="e.g. John Smith"
    ></survey-input-text>

    <survey-input-select
      question="2. What is your favorite UI framework?"
      :options="['React', 'Vue.js', 'Angular']"
    ></survey-input-select>

    <survey-input-radio
      question="3. What backend do you use?"
      :options="['Node.js', 'Laravel', 'Ruby']"
      name="backend"
    ></survey-input-radio>
    <br>
    <button>Submit</button>
  </div>
</template>

<script>
import SurveyInputText from './components/SurveyInputText.vue'
import SurveyInputSelect from './components/SurveyInputSelect.vue'
import SurveyInputRadio from './components/SurveyInputRadio.vue'

export default {
  name: 'app',
  components: {
    surveyInputText: SurveyInputText,
    surveyInputSelect: SurveyInputSelect,
    surveyInputRadio: SurveyInputRadio
  }
}

</script>
