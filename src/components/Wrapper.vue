<template>
    <div class="container">
      <component-1/>
      <component-2/>
      <component-3/>
      <component-4/>
    </div>

</template>
<style>

</style>
<script>

import Component1 from './Component1.vue';
import Component2 from './Component2.vue';
import Component3 from './Component3.vue';
import Component4 from './Component4.vue';

export default {

  components:{
  'component-1':Component1,
   'component-2':Component2,
   'component-3':Component3,
   'component-4':Component4,


  }
}
</script>


