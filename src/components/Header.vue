<template>
  <div class="header">
    <img src="../assets/dc-logo.png" alt="" />
    <ul class="headmen">
      <li v-for="button in list" :key="button.id">
        {{ button.label }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      list: [
        {
          label: "CHARACTERS",
          id: "0123",
        },
        {
          label: "COMICS",
          id: "0124",
        },
        {
          label: "MOVIES",
          id: "0125",
        },
        {
          label: "TV",
          id: "0126",
        },
        {
          label: "GAMES",
          id: "0127",
        },
        {
          label: "COLLECTIBLES",
          id: "0128",
        },
        {
          label: "VIDEOS",
          id: "0129",
        },
        {
          label: "FANS",
          id: "0130",
        },
        {
          label: "NEWS",
          id: "0131",
        },
        {
          label: "SHOP",
          id: "0132",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scope>
@import "../style/header.scss";
</style>
