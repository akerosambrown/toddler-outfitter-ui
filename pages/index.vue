
import { NuxtLink } from '#build/components';
<template>
  <div class="flex flex-col items-center justify-center h-full">
    <h1>Let's get dressed!</h1>
    <NuxtLink to="/topBottomBoth" class="btn flex justify-center items-center">
      Start!
    </NuxtLink>
  </div>
</template>

<style lang="scss">
h1 {
  font-size: 200px;
  text-align: center;
  line-height: 1;
  -webkit-text-stroke: 7.5px black; /* width and color */
  text-shadow: 4px 4px 5px rgba(0,0,0,1);
  letter-spacing: 5px;
  color: rgba(255, 229, 0, 1)
}
.btn {
  font-size: 64px;
  letter-spacing: 10px;
  line-height: 1;
  margin-top: 6rem;
  padding-top: 1.25rem;
  width: 40%;
  height: 140px;
  border-radius: 20px;
  border: 7.5px solid black;
  background-color: rgba(248, 42, 42, 1);
  box-shadow: 0px 4px 5px rgba(0,0,0,0.5);
  color: white;
  &:hover {
    box-shadow: none;
    background-color: rgba(67, 240, 52, 1);
    color: black;
    transition: 0.25s ease-out;
  }
}
</style>