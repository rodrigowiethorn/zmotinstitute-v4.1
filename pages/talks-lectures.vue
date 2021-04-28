<template>
    <main>

        <SectionTalksLecturesHero />

        <SectionTalksLectureWhyHire />
        
        <SectionTalksLecturesOurTalks />

        <SectionTalksLecturesGallery />

        <SectionTalksLectureLeadForm />

        <SectionTalksLectureFAQ />



    </main>
</template>

<script>
export default {
    components: {
      SectionTalksLecturesHero: () => import('~/components/Production/TalksLectures/SectionTalksLecturesHero'),
      SectionTalksLecturesOurTalks: () => import('~/components/Production/TalksLectures/SectionTalksLecturesOurTalks'),
      SectionTalksLectureWhyHire: () => import('~/components/Production/TalksLectures/SectionTalksLectureWhyHire'),
      SectionTalksLectureLeadForm: () => import('~/components/Production/TalksLectures/SectionTalksLectureLeadForm'),
      SectionTalksLecturesGallery: () => import('~/components/Production/TalksLectures/SectionTalksLecturesGallery'),
      SectionTalksLectureFAQ: () => import('~/components/Production/TalksLectures/SectionTalksLectureFAQ'),

    }
}
</script>
