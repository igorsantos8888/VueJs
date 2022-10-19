<template>
  <div>
    <h1>Hoje tem Flamengo!</h1>
    <p>Meu nome é {{ nome }} e trabalho como {{ profissao }}!</p>
  </div>
</template>

<script>
export default {
  name: "PrimeiroComponente",
  data() {
    return {
      nome: "Igor",
      profissao: "Desenvolvedor",
    };
  },
};
</script>
