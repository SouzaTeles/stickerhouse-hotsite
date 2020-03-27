<template>
  <Layout class="home">
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="Sticker House" src="~/stickerhouse-logo.png"/>
    <h1>Sticker House</h1>
    <p>Nossa loja virtual encontra-se em desenvovimento. Em breve estaremos disponiveis para que você possa adiquirir seus stickers favoritos com toda a facilidade e sem precisar sair de sua casa!</p>
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
.home h1 {
  display: none;
}
.home-links a {
  margin-right: 1rem;
  text-decoration: none;
  font-weight: 500;
  color: #333;
  transition: 0.3s;
}
.home-links a:hover {
  color: #111;
  text-decoration: underline;
}
</style>
