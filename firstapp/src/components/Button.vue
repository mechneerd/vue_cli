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
        console.log('okay')
    }
 }
}
</script>
