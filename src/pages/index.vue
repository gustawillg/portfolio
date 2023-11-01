<template>
  <body class="relative font-sans text-black">
    <div id="app" data-server-rendered="true" data-v-app>
      <header data-v-14f5f3d7 class="header z-40">
        <nav class="bg-transparent">
          <div class="flex items-center justify-center">
            <div class="relative h-16 flex items-center justify-between">
              <div class="absolute inset-y-0 left-0 flex items-center sm:hidden" />
              <div class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start">
                <div class="flex flex-shrink-0 items-center" />
                <div class="hidden sm:ml-6 sm:block">
                  <div class="flex space-x-4">
                    <a href="#" class="px-3 py-2 text-sm font-medium text-black hover:text-orange">Projetos</a>
                    <a href="#" class="px-3 py-2 text-sm font-medium text-black hover:text-orange">Skills</a>
                    <a href="#" class="px-3 py-2 text-sm font-medium text-black hover:text-orange">Contato</a>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Mobile menu, show/hide based on menu state. -->
          <div id="mobile-menu" class="sm:hidden">
            <div class="px-2 pb-3 pt-2 space-y-1">
              <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
              <a href="#" class="block rounded-md px-4 py-4 text-sm font-medium text-black hover:text-orange"><svg
                xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="h-6 w-6"
              >
                <path
                  stroke-linecap="round" stroke-linejoin="round"
                  d="M17.25 6.75L22.5 12l-5.25 5.25m-10.5 0L1.5 12l5.25-5.25m7.5-3l-4.5 16.5"
                />
              </svg></a>
              <a href="#" class="block rounded-md px-4 py-4 text-sm font-medium text-black hover:text-orange"><svg
                xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="h-6 w-6"
              >
                <path
                  stroke-linecap="round" stroke-linejoin="round"
                  d="M2.25 18.75a60.07 60.07 0 0115.797 2.101c.727.198 1.453-.342 1.453-1.096V18.75M3.75 4.5v.75A.75.75 0 013 6h-.75m0 0v-.375c0-.621.504-1.125 1.125-1.125H20.25M2.25 6v9m18-10.5v.75c0 .414.336.75.75.75h.75m-1.5-1.5h.375c.621 0 1.125.504 1.125 1.125v9.75c0 .621-.504 1.125-1.125 1.125h-.375m1.5-1.5H21a.75.75 0 00-.75.75v.75m0 0H3.75m0 0h-.375a1.125 1.125 0 01-1.125-1.125V15m1.5 1.5v-.75A.75.75 0 003 15h-.75M15 10.5a3 3 0 11-6 0 3 3 0 016 0zm3 0h.008v.008H18V10.5zm-12 0h.008v.008H6V10.5z"
                />
              </svg>

              </a>
              <a href="#" class="block rounded-md px-4 py-4 text-sm font-medium text-black hover:text-orange"><svg
                xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="h-6 w-6"
              >
                <path
                  stroke-linecap="round" stroke-linejoin="round"
                  d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"
                />
              </svg>
              </a>
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
              Sempre me conectei com a tecnologia, desde novo, seja com games ou pesquisando sobre, ja que meu primeiro
              computador foi quando tinha apenas 6 anos. Com isso me conectei rapidamente com a programação, com meus 13
              anos ja tive meu primeiro contato.
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
