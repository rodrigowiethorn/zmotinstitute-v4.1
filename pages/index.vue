<template>
   <div>
        <!-- <lazy-hydrate when-visible>
          <SectionBanner />
        </lazy-hydrate>

        <lazy-hydrate when-visible>
          <SectionWhyZmot />
        </lazy-hydrate> -->
    <SectionBanner />

     <SectionLogoCloud />

    <SectionWhyZmot />

    <SectionExperts />

    <SectionServices />

    <SectionReviews />

    <SectionBlogHome />

    <SectionNewsletter />


    </div>
</template>

<script>


export default {
  components: {
      SectionBanner: () => import('~/components/Production/Home/SectionBanner'),
      SectionLogoCloud: () => import('~/components/Production/Home/SectionLogoCloud'),
      SectionWhyZmot: () => import('~/components/Production/Home/SectionWhyZmot'),
      SectionExperts: () => import('~/components/Production/Home/SectionExperts'),
      SectionServices: () => import('~/components/Production/Home/SectionServices'),
      SectionReviews: () => import('~/components/Production/Home/SectionReviews'),
      SectionBlogHome: () => import('~/components/Production/Home/SectionBlogHome'),
      SectionNewsletter: () => import('~/components/Production/Home/SectionNewsletter'),
  }
}
</script>

<style>

</style>
