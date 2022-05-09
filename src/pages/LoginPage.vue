<template>
  <q-page padding class="flex flex-center">
    <div class="full-width" style="max-width: 350px">
      <h5 class="q-my-md text-center">login</h5>
      <q-card>
        <q-card-section>
          <form action="">
            <q-input
              filled
              label="email"
              placeholder="email@example.com"
              class="q-mb-md"
            >
            </q-input>
            <q-input
              filled
              label="password"
              type="password"
              class="q-mb-sm"
            ></q-input>
            <q-checkbox :model-value="true" label="remember me"></q-checkbox>
            <q-btn label="login" class="full-width" color="primary"></q-btn>
          </form>
        </q-card-section>
      </q-card>
    </div>
  </q-page>
</template>

<script>
export default {
  // name: 'PageName',
};
</script>
