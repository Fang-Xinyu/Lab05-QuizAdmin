<template>
  <div id="app">
   <!-- <user-view> </user-view> -->
   <!-- <question-view> </question-view> -->
   <router-view></router-view>
  </div>
</template>

<script>
// import UserView from '@/views/UserView.vue'
// import QuestionView from '@/views/QuestionView.vue'

export default {
  components: {
    // QuestionView
  },
  data() {
    return {
      massage: 'Hello Vue!',
    };
  },
  methods: {

  },
};
</script>
