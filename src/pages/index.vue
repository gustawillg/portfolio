<template>
  <body class="relative font-sans text-black">
    <div id="app" data-server-rendered="true" data-v-app>
      <header data-v-14f5f3d7 class="header z-40">
        <nav class="bg-transparent">
          <div class="mx-auto max-w-7xl px-2 lg:px-8 sm:px-6">
            <div class="relative h-16 flex items-center justify-between">
              <div class="absolute inset-y-0 left-0 flex items-center sm:hidden" />
              <div class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start">
                <div class="flex flex-shrink-0 items-center" />
                <div class="hidden sm:ml-6 sm:block">
                  <div class="flex space-x-4">
                    <a
                      href="#" class="rounded-md bg-white px-3 py-2 text-sm font-medium text-black"
                      aria-current="page"
                    >Dashboard</a>
                    <a
                      href="#"
                      class="rounded-md px-3 py-2 text-sm font-medium text-black hover:bg-gray-700 hover:text-white"
                    >Team</a>
                    <a
                      href="#"
                      class="rounded-md px-3 py-2 text-sm font-medium text-black hover:bg-gray-700 hover:text-white"
                    >Projects</a>
                    <a
                      href="#"
                      class="rounded-md px-3 py-2 text-sm font-medium text-black hover:bg-gray-700 hover:text-white"
                    >Calendar</a>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Mobile menu, show/hide based on menu state. -->
          <div id="mobile-menu" class="sm:hidden">
            <div class="px-2 pb-3 pt-2 space-y-1">
              <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
              <a
                href="#" class="block rounded-md bg-gray-900 px-3 py-2 text-base font-medium text-white"
                aria-current="page"
              >Dashboard</a>
              <a
                href="#"
                class="block rounded-md px-3 py-2 text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white"
              >Team</a>
              <a
                href="#"
                class="block rounded-md px-3 py-2 text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white"
              >Projects</a>
              <a
                href="#"
                class="block rounded-md px-3 py-2 text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white"
              >Calendar</a>
            </div>
          </div>
        </nav>
      </header>
      <main class="of-x-hidden px-7 py-10">
        <div
          class="pointer-events-none fixed bottom-0 left-0 right-0 top-0 print:hidden"
          style="z-index:-1; -webkit-mask-image: radial-gradient(circle, transparent, black)"
        >
          <canvas width="1920" height="983" style="width: 1920px; height: 983px;" />
        </div>
        <div class="m-auto mb-8 prose">
          <h1 class="slide-enter-50 mb-0">
            Gustavo Willian
          </h1>
        </div>
        <article>
          <div class="slide-enter-content m-auto prose">
            <p>
              Olá, sou o Gustavo e seja bem vindo ao meu portfolio!
            </p>
            <p>
              Atualmente, estudo frontend, porém amo aprender de tudo, atualmente estudo php e backend,
              <a href="/projects">todos meus projetos estão aqui</a>.
            </p>
            <div flex-auto="" />
            <p>Me ache em:</p>
            <p flex="~ gap-3 wrap" class="mt--2!">
              <a href="https://github.com/coartem" target="_blank"><span op75="" i-simple-icons-github="" /> GitHub</a><a
                href="https://elk.zone/m.webtoo.ls/@antfu" target="_blank"
              />
            </p>
          </div>
        </article>
      </main>
    </div>
  </body>
</template>
