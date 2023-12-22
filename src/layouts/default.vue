<!--
 * @Author: 高江华 g598670138@163.com
 * @Date: 2023-07-29 16:48:52
 * @LastEditors: 高江华
 * @LastEditTime: 2023-12-22 20:09:22
 * @Description: file content
-->
<template>
    <div class="main">
        <AppHeader name="header" />
        <slot />
        <AppFooter name="footer" />
    </div>
</template>

<script setup lang='ts'>
import AppHeader from './header/index.vue'
import AppFooter from './footer/index.vue'
</script>