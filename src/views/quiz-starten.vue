<template>
  <div class="quiz-starten-container">
    <img
      alt="image"
      src="/playground_assets/logo%203-600w.png"
      class="quiz-starten-image"
    />
  </div>
</template>

<script>
export default {
  name: 'QuizStarten',
  metaInfo: {
    title: 'Quiz-starten - Opulent High Goldfish',
    meta: [
      {
        property: 'og:title',
        content: 'Quiz-starten - Opulent High Goldfish',
      },
    ],
  },
}
</script>

<style scoped>
.quiz-starten-container {
  width: 100%;
  display: flex;
  overflow: auto;
  box-shadow: 5px 5px 10px 0px #d4d4d4;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.2) 0%, rgba(0, 0, 0, 0.8) 100%);
}
.quiz-starten-image {
  top: 316px;
  left: 290px;
  width: 576px;
  height: 190px;
  position: absolute;
  align-self: center;
  object-fit: cover;
  border-color: var(--dl-color-gray-black);
  border-width: 4px;
  border-radius: 30px;
}
</style>
