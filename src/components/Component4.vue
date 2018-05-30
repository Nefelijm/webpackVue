<template>
  <div class="col-md-3 theresult">
                  <p>Tu cuota mensual es</p>
                  <h2><span>S/</span>1,074<span>.89</span></h2>
                  <button class="calc" onclick="dataLayer.push({'SolicitarPrestamo':true,'Interact':true,'MontoPrestamo':document.getElementsByName('monto')[0].value,'PlazoPrestamo':document.getElementsByName('tiempo_prestamo')[0].value,'RiesgoPrestamo':document.getElementsByName('eriesgo')[0].value})">Solicitar</button>
	</div>

</template>
<style>

</style>
<script>
import {EventBus} from './EventBus.vue';
export default {

}
</script>
