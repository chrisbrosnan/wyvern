<template>
  <div class="page">
    <HeroBlock />
    <ServicesBlock />
    <FooterBlock />
  </div>
</template>

<script>
import MenuBlock from '@/components/header/menu';
import HeroBlock from '@/components/index/hero';
import ServicesBlock from '@/components/index/services';
import FooterBlock from '@/components/footer/footer';

export default {
  name: 'basic-page',
  components: { MenuBlock, HeroBlock, ServicesBlock, FooterBlock }
}
</script>