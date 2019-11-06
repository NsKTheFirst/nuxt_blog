<template>
  <section class="posts-list">
    <PostPreview
      id="1"
      thumbnail="https://media.dhakatribune.com/uploads/2019/08/bigstock-creating-software-and-website-295627450-1564745123094.jpg"
      title="Hello there!"
      previewText="This is my first post!"/>
    <PostPreview
      id="2"
      thumbnail="https://media.dhakatribune.com/uploads/2019/08/bigstock-creating-software-and-website-295627450-1564745123094.jpg"
      title="Hello there - the second time!"
      previewText="This is my second post!"/>
    <PostPreview
      id="3"
      thumbnail="https://media.dhakatribune.com/uploads/2019/08/bigstock-creating-software-and-website-295627450-1564745123094.jpg"
      title="Hi!"
      previewText="This is my third post!"/>
  </section>
</template>

<script>
  import PostPreview from '@/components/Posts/PostPreview'
  export default {
    name: "PostList",
    components: {
      PostPreview
    }
  }
</script>

<style scoped>
  .posts-list {
    display: flex;
    padding: 20px;
    box-sizing: border-box;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
  }
</style>
