<script setup>
import HomeCard from "../components/HomeCard.vue";
</script>

<template>
  <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Podcasts to make you smarter
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
      <HomeCard
        image="/images/homecard/lonely.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        image="/images/homecard/classic.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="md:block hidden"
        image="/images/homecard/party.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="lg:block hidden"
        image="/images/homecard/rock.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="xl:block hidden"
        image="/images/homecard/work.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
    </div>
  </div>
  <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Recomended Radio
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
      <HomeCard
        image="/images/homecard/work.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        image="/images/homecard/sports.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="md:block hidden"
        image="/images/homecard/nature.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="lg:block hidden"
        image="/images/homecard/film.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="xl:block hidden"
        image="/images/homecard/work.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
    </div>
  </div>
  <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Recomended Songs
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
      <HomeCard
        image="/images/homecard/party.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        image="/images/homecard/work.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="md:block hidden"
        image="/images/homecard/rock.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="lg:block hidden"
        image="/images/homecard/travel.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="xl:block hidden"
        image="/images/homecard/film.png"
        title="Title is here"
        subTitle="Subtitle is here"
      />
    </div>
  </div>
</template>
