<template>
  <v-container>
    <v-row>
      <v-col
        v-for="count in 12"
        :key="count"
        cols="12"
        sm="6"
        md="4"
        lg="3"
      >
        <!-- 디폴트 12/ 디스플레이 크기별로 cols 크기 조정 -->
        <!-- cols 최대 12까지 지정가능 -->
        <v-card class="pa-3">
          Col
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
export default {

}
</script>
<style lang="">

</style>
