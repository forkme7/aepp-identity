<template>
  <div class="app-browser screen" :class="{ loading }">
    <iframe ref="appframe" id="appframe" class="nomargin" :src="path" />

    <div class="loader" />

    <quick-id showBackButton />
  </div>
</template>

<script src="./AppBrowser.js" />
<style lang="scss" scoped src="./AppBrowser.scss" />
