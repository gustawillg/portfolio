<script setup>
const products = [
  {
    id: 1,
    name: 'Site de reserva de hoteis',
    href: '#',
    imageSrc: '/images/hotel.png',
    imageAlt: 'Site de reserva de hoteis.',
  },
// More products...
]
</script>

<template>
  <div cid="app" data-server-rendered="true" data-v-app>
    <header data-v-14f5f3d7 class="header z-40">
      <nav class="bg-transparent">
        <div class="mx-auto max-w-7xl px-4">
          <div class="flex items-center justify-between py-4">
            <a href="/" class="text-3 text-black sm:text-4">G.w</a>
            <div class="md:flex space-x-4">
              <a href="/projetos" class="text-3 text-black sm:text-4 hover:text-orange">Projetos</a>
              <a href="/skills" class="text-3 text-black sm:text-4 hover:text-orange">Skills</a>
              <a href="/skills" class="text-3 text-black sm:text-4 hover:text-orange">Contato</a>
            </div>
          </div>
        </div>
      </nav>
    </header>
    <div class="m-auto mb-8 text-center prose">
      <h1 class="slide-enter-50 mb-0 text-2xl font-bold tracking-tight text-gray-900">
        Projetos
      </h1>
    </div>
    <div class="mx-auto max-w-2xl px-4 py-16 lg:max-w-7xl lg:px-8 sm:px-6 sm:py-24">
      <div class="grid grid-cols-1 mt-6 gap-x-6 gap-y-10 lg:grid-cols-4 sm:grid-cols-2 xl:gap-x-8">
        <div v-for="product in products" :key="product.id" class="group relative">
          <div class="aspect-h-1 aspect-w-1 lg:aspect-none w-full overflow-hidden rounded-md bg-gray-200 lg:h-80 group-hover:opacity-75">
            <img :src="product.imageSrc" :alt="product.imageAlt" class="h-full w-full object-cover object-center lg:h-full lg:w-full">
          </div>
          <div class="mt-4 flex justify-between">
            <div>
              <h3 class="text-sm text-gray-700">
                <a :href="product.href">
                  <span aria-hidden="true" class="absolute inset-0" />
                  {{ product.name }}
                </a>
              </h3>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
