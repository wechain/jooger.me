<!--
 * @desc Loading
 * @author Jooger <iamjooger@gmail.com>
 * @date 2018-09-24 13:32:09
 -->
<template>
  <div class="loading" :class="[`loading-${size}`, dark && 'loading-dark']">
    <div class="wrapper">
      <div class="spinner">
        <svg class="circular" viewBox="25 25 50 50">
          <circle class="path" cx="50" cy="50" r="20" fill="none" stroke-width="5" stroke-miterlimit="10"></circle>
        </svg>
      </div>
      <div class="text" v-if="!noText">{{ text }}</div>
    </div>
  </div>
</template>

<script lang="ts" src="./index.ts"></script>

<style lang="stylus" scoped src="./index.styl"></style>
