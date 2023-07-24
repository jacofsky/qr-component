<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;800&display=swap');

main {
  font-family: 'Outfit', sans-serif;
  background-color: hsl(212, 45%, 89%);
  height: 100vh;
  width: 100vw;
  display: flex;
  align-items: center;
  justify-content: center;
}

section {
  background-color: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 2rem;
  border-radius: 1rem;
}

span {
  font-size: 15px;
  color: hsl(220, 15%, 55%);
  font-weight: 400;
  text-align: center;
  width: 16rem;
}

p {
  font-weight: 800;
  color: hsl(218, 44%, 22%);
  width: 16rem;
  font-size: 20px;
  text-align: center;
}

img {
  width: 16rem;
  border-radius: 1rem;
}
</style>

<template>
  <main>
    <section>
      <img src="./assets/image-qr-code.png" alt="qr">
      <p>Improve your front-end skills by building projects</p>
      <span>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</span>
    </section>
  </main>
</template>

<script setup lang="ts">

</script>