<demo>
按钮类型
</demo>

<template>
  <div>
    <Button level='main'>主按钮</Button>
    <Button theme='text'>文本按钮</Button>
    <Button theme='link'>链接按钮</Button>
  </div>
</template>

<script lang='ts'>
import Button from '../lib/Button.vue'

export default {
  components: {
    Button
  }
}
</script>