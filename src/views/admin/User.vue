<template>
  <div class="flex flex-wrap mt-4">
    <div class="w-full mb-12 px-4">
      <card-user tableTitle="Danh sách tài khoản" />
    </div>
  </div>
</template>
<script>
import CardUser from "@/components/Cards/CardUser.vue";

export default {
  components: {
    CardUser,
  },
};
</script>
