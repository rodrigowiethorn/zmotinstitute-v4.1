<template>
    <main>

        <SectionTalksLecturesHero />

        <SectionTalksLecturesFeaturesList />

        <SectionZmotAuditLeadForm />

        <SectionTalksLecturesGallery />

    </main>
</template>

<script>
export default {
    components: {
      SectionTalksLecturesHero: () => import('~/components/Production/TalksLectures/SectionTalksLecturesHero'),
      SectionTalksLecturesFeaturesList: () => import('~/components/Production/TalksLectures/SectionTalksLecturesFeaturesList'),
      SectionZmotAuditLeadForm: () => import('~/components/Production/ZmotAudit/SectionZmotAuditLeadForm'),
      SectionTalksLecturesGallery: () => import('~/components/Production/TalksLectures/SectionTalksLecturesGallery'),

    }
}
</script>
