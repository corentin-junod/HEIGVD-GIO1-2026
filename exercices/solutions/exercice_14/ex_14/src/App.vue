<script>
  import Openlayers from './Openlayers.vue';
  import Giro3D from './Giro3D.vue';

  export default {
		components: {
			Openlayers,
      Giro3D
		}
	}
</script>

<template>
  <h1>Openlayers & Giro3D</h1>
  <div class="mainContent">
      <Openlayers />
      <Giro3D />
  </div>
</template>

<style>
.mainContent{
  display: flex;
}
</style>
