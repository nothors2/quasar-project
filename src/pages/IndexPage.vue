<template>
  <q-page padding>
    <q-card>
      <q-card-section>
        <q-btn label="click" color="orange"></q-btn
      ></q-card-section>
      <q-card-section class="bg-blue text-white"> My card </q-card-section>
      <q-card-section>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, iure.
        Maiores dignissimos pari rehenderit ea omnis quibusdam aut odit, tenetur
        esse.
      </q-card-section>
      <q-card-section>
        <q-select filled :options="['test', 'test2']" v-model="selected">
        </q-select>
      </q-card-section>
    </q-card>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
  data() {
    return {
      selected: null,
    };
  },
});
</script>
