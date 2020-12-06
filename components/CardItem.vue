<template>
  <thead>
    <tr>
      <th>技術</th>
      <th>経験年数</th>
      <th>スキル</th>
    </tr>
  </thead>
</template>

<script lang="ts">
import Vue from 'vue'
interface Skill {
  name: string
  age: string
  point: string
}

export default Vue.extend({
  name: 'CardItem',
  /*
  data: {
    skill: {
      required: true,
      type: Array as PropType<Skill[]>,
    },
  },
  */
})
</script>
<!--style lang="scss" scoped-->
<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
