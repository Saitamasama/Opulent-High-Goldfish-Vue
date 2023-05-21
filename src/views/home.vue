<template>
  <div class="home-container">
    <img
      alt="image"
      src="/playground_assets/logo%203-600w.png"
      class="home-image"
    />
    <router-link to="/quiz-starten" class="home-button button">
      Quiz starten
    </router-link>
  </div>
</template>

<script>
export default {
  name: 'Home',
  metaInfo: {
    title: 'Opulent High Goldfish',
    meta: [
      {
        property: 'og:title',
        content: 'Opulent High Goldfish',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
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
.home-image {
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
.home-button {
  top: 541px;
  left: 426px;
  color: var(--dl-color-gray-black);
  width: 327px;
  height: 56px;
  padding: var(--dl-space-space-unit);
  position: absolute;
  font-size: 18px;
  text-align: center;
  font-family: Comic Sans MS;
  border-width: 4px;
  border-radius: 15px;
  text-decoration: none;
  background-color: var(--dl-color-primary-700);
}
</style>
