<template>
  <header class="shadow w-screen">
    <nav class="flex items-center justify-between flex-wrap bg-green-400 p-6">
      <div class="flex items-center flex-shrink-0 text-white mr-6">
        <ex-icon class="mr-2" />
        <router-link
          :to="{ name: 'home' }"
          class="font-semibold text-xl tracking-tight"
        >ExchangeSystem</router-link>
      </div>
      <div class="hidden sm:block w-full block flex-grow lg:flex lg:items-center lg:w-auto">
        <div class="text-sm lg:flex-grow"></div>
      </div>
    </nav>
  </header>
</template>

<script>
import ExIcon from "@/components/ExIcon";

export default {
  name: "ExHeader",
  components: { ExIcon }
};
</script>