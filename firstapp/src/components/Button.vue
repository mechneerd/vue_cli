<template>
    <button @click="newfun()" class="btn" :style="{background:color}">{{text}}</button>
</template>

<script>
export default {
 name:'Button',
 props:{
    text:String,
    color:String,
 },
 methods:{
    newfun(){
        console.log('Let see if it works')
    }
 }
}
</script>
