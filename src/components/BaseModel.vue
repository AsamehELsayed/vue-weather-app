<template>

  <div class="w-screen h-screen left-0 top-0 bg-black opacity-30 absolute -z-10" @click='close'></div>
  <div class="z-10  container absolute rounded-md bg-white  p-10 border  w-1/2 text-3xl top-1/4 left-1/4">
    <slot></slot>
     </div>
</template>
<script>
export default {
name:'BaseModel',
methods:{
    close(){
      this.$emit('close')
    }
  }
}
</script>

<style>

</style>