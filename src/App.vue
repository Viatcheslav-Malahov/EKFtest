<template>
  <div class="main">
    <HelloWorld msg="Table" />
    <table>
      <tr>
        <td>name</td>
        <td>vendor_code</td>
        <td>series</td>
        <td>price</td>
        <td></td>
      </tr>
    </table>
  </div>
</template>

<script setup>
import HelloWorld from "./components/HelloWorld.vue";

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style scoped lang="scss">
.main {
  padding: 5%;
  tr {
    td {
      padding: 10px;
      button {
        padding: 5px;
      }
    }
  }
}
</style>
