<template>
    <div class="separationHeader">
        <h2>Colecionadores</h2>
        <button>Ver todos</button>
    </div>
</template>

<script>
export default {
  name: "OsColecionadores",
  props: {
    msg: String,
  },
};
</script>

<style scoped>

.separationHeader {
  display: flex;
  justify-content: space-between;
}

button {
  width: 245px;
  height: 56px;
  left: 352px;
  top: 624px;

  background: linear-gradient(97.86deg, #ff8d8d -38.38%, #f7fc0e 71.88%);
  border-radius: 6px;
}
</style>