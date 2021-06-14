<template>
 <div >
   <button class="rk-button" :class="[`rk-button--${type}`]">
     <span>
      <slot></slot>
     </span>
   </button>
 </div>
</template>

<script>
export default {
 name:"RkButton",
 props:{
   type:{
     type:String,
     default:'default'
   }
 },
 data() {
 return {

 }
 },

 methods: {

 }
};
</script>

<style scoped>
.rk-button{
  display: inline-block;
  background: #fff;
  border: 1px solid blue;
  color: pink;
  text-align: center;
  margin: 0;
  transition: 0.1s;
  font-weight: 500;
  outline: none;
  line-height: 1;
  cursor: pointer;
  white-space: nowrap;
  border-radius: 8px;
  width: 80px;
  height: 44px;
}
.rk-button--normal{
  display: inline-block;
  /* background: #fff; */
  border: 1px solid yellow;
  color: gray;
  text-align: center;
  margin: 0;
  transition: 0.1s;
  font-weight: 600;
  outline: none;
  line-height: 1;
  cursor: pointer;
  white-space: nowrap;
  border-radius: 8px;
  width: 80px;
  height: 44px;
  background-color: blueviolet;
}
.rk-button--danger{
  display: inline-block;
  /* background: #fff; */
  border: 1px solid seagreen;
  color: coral;
  text-align: center;
  margin: 0;
  transition: 0.1s;
  font-weight: 600;
  outline: none;
  line-height: 1;
  cursor: pointer;
  white-space: nowrap;
  border-radius: 8px;
  width: 80px;
  height: 44px;
  background-color: red;
}
</style>
