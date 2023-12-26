<template>
  <div>
    <QRGenerator />
  </div>
</template>

<script>
import { QRGenerator } from "ui-lib-utils";
import "ui-lib-utils/dist/ui-lib-utils.css";

export default {
  name: "App",
  components: {
    QRGenerator,
  },
};
</script>

<style>
.QRGenerator {
  margin: 50px;
  display: flex;
  justify-content: center;
  flex-direction: row;
}
</style>
