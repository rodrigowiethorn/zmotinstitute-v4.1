<template>
    
    <main>

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
      SectionOnlineCoursesLeadForm: () => import('~/components/Production/OnlineCourses/SectionOnlineCoursesLeadForm')
    //   SectionZmotAuditfeaturesList: () => import('~/components/Production/ZmotAudit/SectionZmotAuditfeaturesList'),
    //   SectionZmotAuditFAQ: () => import('~/components/Production/ZmotAudit/SectionZmotAuditFAQ'),
    //   SectionZmotAuditLeadForm: () => import('~/components/Production/ZmotAudit/SectionZmotAuditLeadForm')

  }
}
</script>