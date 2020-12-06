<template>
  <thead class="index">
    <tr>
      <th>技術</th>
      <th>経験年数</th>
      <th>スキル</th>
    </tr>
  </thead>
</template>

<script lang="ts">
import Vue from 'vue'
// TODO TSを使うように調整
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
<style lang="scss" scoped>
.index {
  > .row {
    display: flex;
    border-bottom: solid 2px gray;
    padding: 10px 0;
    > .date_published {
      width: 30%;
    }
    > .title {
      width: 30%;
    }
  }
}
</style>
