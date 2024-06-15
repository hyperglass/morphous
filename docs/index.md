---
layout: home

hero:
  name: Morphous
  text: A Practical Approach for Modding Android

  image:
      light: 'https://i.ibb.co/6v8DS91/morphous-logo-prototype-light.png'
      dark: 'https://i.ibb.co/rkHDpYN/morphous-logo-prototype-dark.png'
      alt: Morphous


features:
  - icon:
      src: https://i.ibb.co/F0FCmxR/poco-f5.png
      width: 162
    title: Poco F5
    details: marble
    link: https://hyperglass.github.io/morphous-marble/

  - icon:
      src: https://xdaforums.com/data/xda/device/icon/20/2079.jpg?1696672907
      width: 162
    title: Pixel 8 Pro
    details: husky (Coming Soon)
    link:

  - icon:
      src: https://xdaforums.com/data/xda/device/icon/16/1651.jpg?1622124707
      width: 162
    title: Redmi Note 10S
    details: rosemary (Coming Soon)
    link:


---

<style>
  div.item {
    width: auto !important;
  }
  div.item h2.title {
    font-size: 20px;
  }
</style>

<script setup>
import { onMounted } from 'vue';

onMounted(() => {
  const links = document.querySelectorAll('a.item');
  console.log(links); // Check if the elements are correctly selected
  if (links.length > 0) {
    links.forEach(link => {
      link.setAttribute('target', '_self');
    });
  }
});
</script>
=



