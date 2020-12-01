<template>
  <lazy-hydrate when-visible>
      <section-banner />
    </lazy-hydrate>


</template>

<script>


export default {
  components: {
      SectionBanner: () => import('~/components/Home/SectionBanner')
      //SectionBlogs: () => import('~/components/Home/SectionBlogs'),
      // SectionSayAboutUs: () => import('~/components/Home/SectionSayAboutUs'),
      // SectionServices: () => import('~/components/Home/SectionServices'),
      // SectionSpecialists: () => import('~/components/Home/SectionSpecialists'),
      // SectionWhyZmot: () => import('~/components/Home/SectionWhyZmot'),
      // 
      // NewsLetter: () => import('~/components/NewsLetter'),
  }
}
</script>

<style>

</style>
