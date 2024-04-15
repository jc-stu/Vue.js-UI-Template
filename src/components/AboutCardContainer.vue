<template>
  <v-container fluid>
    <v-row class="about-card-container">
      <AboutCard
        title_text="关于本博客"
        body_text="基于大前端的博客系统，使用Vue构建"
      />
      <AboutCard
        title_text="小组成员"
        body_text="姜川    罗珺中"
      />
    </v-row>
  </v-container>
</template>

<script>
import AboutCard from "@/components/AboutCard";

export default {
  name: "AboutCardContainer",
  components: {
    AboutCard,
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/shared-styles.scss";

.about-card-container {
  background-color: $views-background-color;
  height: auto;
  margin-top: 2em;
}
</style>
