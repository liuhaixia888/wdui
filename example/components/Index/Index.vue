<template>
  <div class="index-container">
    <wd-header title="Components"></wd-header>
    <wd-cell :title="item" :to="`#/${item.toLowerCase()}`" v-for="item in components" :key="item"></wd-cell>
  </div>
</template>

<script>
export default {
  data() {
    return {
      components: [
        'Toast',
        'MessageBox',
        'Dialog',
        'Lazyload',
        'Button',
        'Search',
        'Picker',
        'Swipe',
        'Switch',
        'Popup',
        'Tooltip',
        'Radio',
        'Checkbox',
        'ImagePreview',
        'ActionSheet',
        'Scroller',
        'Header',
        'Tabbar',
        'Navbar',
        'Cell',
        'Badge'
      ]
    }
  }
}
</script>

<style lang="sass">
.icon-zuosanjiao {
  color: #fff;
}
</style>
