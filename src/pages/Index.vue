<template>
  <Layout class="home">
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="Example image" src="~/favicon.png" width="135"/>

    <h1>Sticker House</h1>

    <p>Nossa loja encontra-se em desenvovimento, e em breve estará disponivel para que você possa adiquirir seus stickers favoritos com toda a facilidade, e sem precisar sair de sua casa!</p>

    <p class="home-links">
      <a href="https://instagram.com/stickerhousebr" target="_blank" rel="noopener">Instagram</a>
      <a href="https://facebook.com/stickerhouse.com.br" target="_blank" rel="noopener">Facebook</a>
    </p>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Sticker House"
  }
};
</script>

<style>
.home {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.home-links a {
  margin-right: 1rem;
}
</style>
