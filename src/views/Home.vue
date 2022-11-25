<template>
  <div class="home">
    <EventCard />
  </div>
</template>

<script>
// @ is an alias to /src
import EventCard from "@/components/EventCard.vue";

export default {
  name: "Home",
  components: {
    EventCard
  }
};
</script>
git config --global user.email "you@example.com"
  git config --global user.name "Your Name"