<template>
    
    <main>

        <SectionZmotAuditHero />

        <SectionZmotAuditfeaturesList />

         <SectionZmotAuditLeadForm />

        
        <!-- <div class="h-1 bg-indigo-700 lg:mx-48 mx-12 mt-12"></div> -->
        
        <SectionZmotAuditFAQ />

    </main>
 

</template>

<script>


export default {
  components: {
      SectionZmotAuditHero: () => import('~/components/Production/ZmotAudit/SectionZmotAuditHero'),
      SectionZmotAuditfeaturesList: () => import('~/components/Production/ZmotAudit/SectionZmotAuditfeaturesList'),
      SectionZmotAuditFAQ: () => import('~/components/Production/ZmotAudit/SectionZmotAuditFAQ'),
      SectionZmotAuditLeadForm: () => import('~/components/Production/ZmotAudit/SectionZmotAuditLeadForm'),
      SectionZmotAuditReviews: () => import('~/components/Production/ZmotAudit/SectionZmotAuditReviews')
      

  }
}
</script>