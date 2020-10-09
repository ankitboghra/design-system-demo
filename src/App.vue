<template>
  <div id="app">
    <!-- <m-header user></m-header> -->
    <Header />
    <Header :user="user" />
    <Button primary label="Primary" />
    <Button label="Button" />
    <Button label="Small" size="small" />
  </div>
</template>

<script>
import { Button, Header } from "matic-design-system";

export default {
  name: "App",
  components: {
    Button,
    Header,
  },
  data: function () {
    return {
      user: {},
    };
  },
};
</script>
