<script setup lang="ts">
import { type TimelinePost } from "../posts";
//import Wishlist from "../../../../Exer06/my-app/src/components/Wishlist.vue";

defineProps<{
  post: TimelinePost;
}>();
</script>
<template>
  <li>
    <span>{{ post.title }}</span
    >&nbsp;|&nbsp;
    <span>{{ post.created.toFormat("d MMM") }}</span>
  </li>
</template>
<style></style>
