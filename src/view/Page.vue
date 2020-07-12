<template>
  <v-app id="inspire">
    <v-container fluid class="pa-0">
      <v-row>
        <DateTimePicker :label="'시작날짜'"></DateTimePicker>
        <DateTimePicker :label="'종료날짜'"></DateTimePicker>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
import DateTimePicker from "./DateTimePicker.vue";

export default {
  name: "Page",
  components: {
    DateTimePicker
  }

}
</script>