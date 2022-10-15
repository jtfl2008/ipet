<template>
  <view class="index">
    <text>{{ msg }}</text>
  </view>
</template>

<script setup>
import { ref } from 'vue';
import './index.scss';
let msg = ref('Hello taro');
</script>
