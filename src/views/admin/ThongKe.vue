<template>
  <div class="flex flex-wrap mt-4">
    <div class="w-full mb-12 px-4">
      <card-thong-ke tableTitle="Danh sách đơn đặt phòng" />
    </div>
  </div>
</template>
<script>
import CardThongKe from "@/components/Cards/CardThongKe.vue";

export default {
  components: {
    CardThongKe,
  },
};
</script>
