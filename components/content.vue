<template>
  <div class="main-content">
    <div class="main-content-stories">
      <div class="story-container-1">
        <div class="story-container-2">
          <div class="story-container-3">
            <Story />
            <Story />
          </div>
        </div>
      </div>
      <div class="main-content-stories-slide-btn" />
    </div>
    <div class="main-content-feed">
      <Feed />
      <Feed />
    </div>
  </div>
</template>
<script>
import Story from '~/components/story.vue'
import Feed from '~/components/feed.vue'
export default {
  components: {
    Story,
    Feed,
  },
}
</script>
