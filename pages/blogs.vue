<template>
    <div>
        <PageTitle pageHeading="Blogs" />
        <BlogsGrid />
    </div>
</template>

<script>
import BlogsGrid from '../components/Blogs/BlogsGrid.vue';

export default {
    components: { BlogsGrid }
}
</script>