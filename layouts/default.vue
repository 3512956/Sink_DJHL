<template>
  <main class="flex flex-col min-h-screen py-10">
    <LayoutsHeader />
    <section class="flex flex-1">
      <div class="container mx-auto">
        <slot />
      </div>
    </section>
    <!-- <LayoutsFooter /> -->
  </main>
</template>
