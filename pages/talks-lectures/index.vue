<template>
    <main>

        <SectionTalksLecturesHero />

        <SectionTalksLecturesFeaturesList />

        <SectionTalksLectureLeadForm />

        <SectionTalksLecturesGallery />

    </main>
</template>

<script>
export default {
    components: {
      SectionTalksLecturesHero: () => import('~/components/Production/TalksLectures/SectionTalksLecturesHero'),
      SectionTalksLecturesFeaturesList: () => import('~/components/Production/TalksLectures/SectionTalksLecturesFeaturesList'),
      SectionTalksLectureLeadForm: () => import('~/components/Production/TalksLectures/SectionTalksLectureLeadForm'),
      SectionTalksLecturesGallery: () => import('~/components/Production/TalksLectures/SectionTalksLecturesGallery'),

    }
}
</script>
