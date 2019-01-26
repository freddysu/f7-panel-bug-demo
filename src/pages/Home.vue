<template>
  <f7-page>
    <f7-navbar sliding>
      <f7-nav-left>
        <f7-link icon-f7="icon-bars" panel-open="left"></f7-link>
      </f7-nav-left>
      <f7-nav-title>
        Home
      </f7-nav-title>
    </f7-navbar>
    <f7-block-title>{{ title }}</f7-block-title>
    <f7-block inner>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit.
      Distinctio est aliquam officiis quaerat placeat, cum explicabo magni
      soluta totam maxime autem minima accusamus eos suscipit dignissimos
      corporis modi voluptatum fugiat!
    </f7-block>
    <f7-list
      v-if="products.length > 0"
      class="product-list"
      :style="{paddingBottom: hideWarning ? 180 : 0}">
      <f7-list-item
        class="product-item"
        :key="product"
        v-for="product in products">
        11123324234
      </f7-list-item>
    </f7-list>
  </f7-page>
</template>
<script>
export default {
  name: 'Home',
  data() {
    return {
      title: 'Hello World',
      products: [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18]
    };
  }
};
</script>
