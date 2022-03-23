<template>
  <TheHeader />
  <!-- Page Header -->
  <PageHeading :title="'Entertainment'" />
 <HeroSection :img="heroImage"/>
  <!--Main Content -->
  <PageContent>
    <template #content>
      <p class="box-content max-w-screen-md mx-auto">
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text ever
        since the 1500s, when an unknown printer took a galley of type and
        scrambled it to make a type specimen book. It has survived not only five
        centuries,
      </p>
    </template>
  </PageContent>
  <!-- Section 1 -->
  <main>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mx-4">
    <section class="flex flex-col bg-gradient-to-r from-blue-400 via-emerald-600 to-pink-400 rounded-sm py-2">
      <header class="grid place-items-center text-center mx-1">
        <h2 class="text-black text-3xl md:text-4xl font-medium">TV SHOWS</h2>
      </header>
      <div class="flex justify-center">
        <ul>
          <li v-for="item in shows" :key="item.id">
            {{ item.name }}
          </li>
        </ul>
      </div>
    </section>
    <!--Section 2-->
    <section class="flex flex-col bg-gradient-to-r from-blue-400 via-emerald-600 to-pink-400 rounded-sm py-2">
      <header class="grid place-items-center text-center mx-1">
        <h2 class="text-black text-3xl md:text-4xl font-medium">
          Talking-Animal Movies
        </h2>
      </header>
      <div class="flex justify-center">
        <ul>
          <li v-for="items in movies" :key="items.id">
            {{ items.name }}
          </li>
        </ul>
      </div>
    </section>
  </div>
    <PageContent :title="sectionTitle">
      <template #content>
        <p class="box-content max-w-screen-md mx-auto">
          ENIMATION festival is an international festival of films made by
          children and youth. There are three categories, depending on the age
          of the authors: MINI (authors up to 10 years), MIDI (authors between
          11 and 14 years), and. MAXI (authors between 15 and 19 years).
        </p>
      </template>
    </PageContent>
  </main>
  <TheFooter :title="'&copy; Maryam Khan 2022'" />
</template>

// imports 
<script setup>
import TheHeader from "./components/TheHeader.vue";
import PageHeading from "./components/PageHeading.vue";
import HeroSection from "./components/HeroSection.vue";
import PageContent from "./components/PageContent.vue";
import TheFooter from "./components/TheFooter.vue";

const sectionTitle = "About";

// shows list
import { ref } from "vue";
const shows = ref([
  { name: "Friends" },
  { name: "Modern Family" },
  { name: "Life in Pieces" },
  { name: "Superstore" },
]);

// movie list
const movies = ref([
  { name: "Bee Movie" },
  { name: "Scooby Dooby Doo" },
  { name: "Kungfu Panda" },
  { name: "Tom and Jerry" },
]);

// hero section
const heroImage = {
  url : "https://images.pexels.com/photos/1190298/pexels-photo-1190298.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260",
  alt: "Hero Image"
}

</script>