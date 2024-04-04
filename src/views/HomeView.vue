<template>
  <div>
    <section class="home" id="home">
      <main class="content">
        <h1>Hello, <span> I am </span> Syifani!</h1>
        <p>
          Bagi saya, kesederhanaan adalah inti dari seni. Semua hal tentang
          minimalis dan estetika.
        </p>
        <buttonc />
      </main>
    </section>
  </div>
</template>

<style scoped>
h1 {
  font-family: "Radley";
  color: #000;
}
.home {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background-size: cover;
  background-position: center;
  position: relative;
}

.home .content {
  padding: 1.4rem 7%;
  max-width: 60rem;
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: repeat(3, auto);
  align-items: center;
  text-align: center;
}

.home .content h1 {
  font-size: 4.5em;
  line-height: 1.2;
  text-align: center;
}

.home .content h1 span {
  color: var(--primary);
}

.home .content p {
  font-size: 2rem;
  margin-top: 1rem;
  line-height: 1.4;
  font-weight: 300;
  text-align: center;
}
</style>

<script setup>
import buttonc from "../components/Button.vue";
</script>
