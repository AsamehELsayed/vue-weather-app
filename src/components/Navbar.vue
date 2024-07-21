<template>
  <header class="bg-blue-300 ">
  <nav class=" container m-auto items-center flex flex-row  w-full h-16">
    <div>
    <h1 class="text-white text-3xl"><i class="pi pi-sun
 pi-spin"></i>
      Weather</h1>
    </div>
    <div class="flex flex-1 gap-1 text-white text-2xl justify-end"> 
      <i class=" pi pi-info-circle" @click="open"/>
      <i class="pi pi-plus"></i>
    </div>
  </nav>
  </header>
</template>

<script >
export default {
  name: 'Navbar',
  methods:{
    open(){
      this.$emit('open')
    }
  }
}
</script>
