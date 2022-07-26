<template>
    <div>
        <hero-section></hero-section>
        <consultant-section :url=url></consultant-section>
        <top-guiders-section :url=url></top-guiders-section>
        <why-you-choose-section></why-you-choose-section>
        <book-appointment-section></book-appointment-section>
        <happy-clients-section></happy-clients-section>
        <become-consultant-section></become-consultant-section>
        <blog-section :url=url></blog-section>
    </div>
</template>

<script>
export default {
    props: ["url"],
};
</script>
