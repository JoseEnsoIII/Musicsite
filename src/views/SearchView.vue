<script setup>
import CategorySelect from "../components/CategorySelect.vue";
</script>

<template>
  <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Recomended Radio
    </button>

    <div class="py-1.5"></div>

    <div
      class="grid xl:grid-cols-5 lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 gap-6"
    >
      <CategorySelect
        category="Podcasts 🎙️"
        image="/images/homecard/lonely.png"
      />
      <CategorySelect
        category="Work Music 🎧"
        image="/images/homecard/work.png"
      />
      <CategorySelect
        category="Classic Music 🎹"
        image="/images/homecard/classic.png"
      />
      <CategorySelect
        category="Rock 🤘"
        image="/images/homecard/rock.png"
      />
      <CategorySelect
        category="Party 🎉"
        image="/images/homecard/party.png"
      />
      <CategorySelect
        category="Sports 🏃"
        image="/images/homecard/sports.png"
      />
      <CategorySelect
        category="Movie 🎬"
        image="/images/homecard/film.png"
      />
      <CategorySelect
        category="Travel 🚐"
        image="/images/homecard/travel.png"
      />
      <CategorySelect
        category="Nature 🌲"
        image="/images/homecard/nature.png"
      />
    </div>
  </div>
</template>
