<template>
  <q-page class>
    <div class="q-ml-xl q-mr-xl q-mt-xl q-mb-xl border-black">teste 1</div>
    <q-page class="container">
      <q-btn color="accent" class="full-width">button1</q-btn>

      <div class="row">
        <div class="col">
          <q-btn color="black">button2</q-btn>
        </div>

        <div class="col">
          <q-btn color="primary">button3</q-btn>
        </div>

        <div class="col">
          <q-btn color="amber">button4</q-btn>
        </div>
        <div class="col">
          <q-btn color="secondary">button4</q-btn>
        </div>
      </div>
      <div class="col">
        <div class="row justify-end">
          <q-btn class="q-sm" color="primary">button1</q-btn>
        </div>

        <div class="row">
          <q-btn class="q-ma-md shadow-24" color="amber">button2</q-btn>
        </div>

        <div class="row justify-end">
          <q-btn class="q-ma-xl" color="secondary">button3</q-btn>
        </div>
      </div>
    </q-page>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>

<style>
.border-black {
  border: 1px solid black;
  text-align: center;
}
</style>
