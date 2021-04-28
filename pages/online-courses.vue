<template>
    
    <main>

        <BreadCrumb />
        
        <SectionOnlineCoursesHero />
        
        <SectionOnlineCoursesFeaturesList />

        <SectionOnlineCoursesLeadForm />

        <SectionOnlineCoursesGallery />

        
    </main>
 

</template>

<script>


export default {
  components: {
      SectionOnlineCoursesHero: () => import('~/components/Production/OnlineCourses/SectionOnlineCoursesHero'),
      SectionOnlineCoursesFeaturesList: () => import('~/components/Production/OnlineCourses/SectionOnlineCoursesFeaturesList'),
      SectionOnlineCoursesGallery: () => import('~/components/Production/OnlineCourses/SectionOnlineCoursesGallery'),
      SectionOnlineCoursesLeadForm: () => import('~/components/Production/OnlineCourses/SectionOnlineCoursesLeadForm'),
      BreadCrumb: () => import('~/components/Inspirations/BreadCrumb/BreadCrumb')
    //   SectionZmotAuditFAQ: () => import('~/components/Production/ZmotAudit/SectionZmotAuditFAQ'),
    //   SectionZmotAuditLeadForm: () => import('~/components/Production/ZmotAudit/SectionZmotAuditLeadForm')

  }
}
</script>