<demo>
按钮尺寸
</demo>

<template>
 <div>
   <div>
     <Button size="big" level='main'>大按钮</Button>
     <Button level='main'>中按钮</Button>
     <Button size="small" level='main'>小按钮</Button>
   </div>
   <div>
     <Button theme="link" size="big">大按钮</Button>
     <Button theme="link">中按钮</Button>
     <Button size="small" theme="link">小按钮</Button>
   </div>
   <div>
     <Button size="big" theme="text">大按钮</Button>
     <Button theme="text">中按钮</Button>
     <Button size="small" theme="text">小按钮</Button>
   </div>
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