<template>
  <div cid="app" data-server-rendered="true" data-v-app>
    <header data-v-14f5f3d7 class="header z-40">
      <nav class="bg-transparent">
        <div class="mx-auto max-w-7xl px-4">
          <div class="flex items-center justify-between py-4">
            <a href="/home" class="text-3 text-black sm:text-4">G.w</a>
            <div class="md:flex space-x-4">
              <!-- Links visíveis na versão desktop -->
              <a href="/projetos" class="text-3 text-black sm:text-4 hover:text-orange">Projetos</a>
              <a href="#" class="text-3 text-black sm:text-4 hover:text-orange">Skills</a>
              <a href="#" class="text-3 text-black sm:text-4 hover:text-orange">Contato</a>
            </div>
          </div>
        </div>
      </nav>
    </header>

    <div class="m-auto mb-8 text-center prose">
      <h1 class="slide-enter-50 mb-0">
        Projetos
      </h1>
    </div>

    <section class="section4 container">
      <div class="display-flex-projects">
        <!-- Botão para ativar modal -->
        <button type="button" class="buttonClass custom-card mx-2 my-2 rounded-4" data-bs-toggle="modal" data-bs-target="#exampleModal1">
          <img src="images/img1.png" alt="certificado-1">
        </button>

        <!-- Modal -->
        <div id="exampleModal1" class="modal fade" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
          <div class="modal-dialog modal-lg">
            <div class="modal-content borda-modal">
              <div class="modal-body rounded-4 text-center">
                <img class="img-fluid mx-auto rounded-4" src="images/img1.png" alt="certificado-1">

                <button type="button" class="buttonClass font-style-title mt-3 rounded-4">
                  <a class="font-color-title" href="https://aluguel-carros-pi.vercel.app/" target="_blank" title="Visitar projeto">
                    <i class="fa-regular fa-file" /> Ver projeto
                  </a>
                </button>
              </div>
            </div>
          </div>
        </div>

        <!-- Botão para ativar modal -->
        <button type="button" class="buttonClass custom-card mx-2 my-2 rounded-4" data-bs-toggle="modal" data-bs-target="#exampleModal2">
          <img class="img-fluid mx-auto" src="images/img2.png" alt="certificado-1">
        </button>

        <!-- Modal2 -->
        <div id="exampleModal2" class="modal fade" tabindex="-1" aria-labelledby="exampleModalLabel" style="display: none;" aria-hidden="true">
          <div class="modal-dialog modal-lg">
            <div class="modal-content borda-modal">
              <div class="modal-body rounded-4 text-center">
                <img class="img-fluid mx-auto rounded-4" src="images/img2.png" alt="certificado-1">

                <button type="button" class="buttonClass font-style-title mt-3 rounded-4">
                  <a href="https://cruise-on-douglas-to.vercel.app/" target="_blank" title="Visitar projeto" class="font-color-title">
                    <i class="fa-regular fa-file" /> Ver projeto
                  </a>
                </button>
              </div>
            </div>
          </div>
        </div>

        <!-- Botão para ativar modal -->
        <button type="button" class="buttonClass custom-card mx-2 my-2 rounded-4" data-bs-toggle="modal" data-bs-target="#exampleModal3">
          <img class="img-fluid mx-auto" src="images/img3.png" alt="certificado-1">
        </button>

        <!-- Moda3 -->
        <div id="exampleModal3" class="modal fade" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
          <div class="modal-dialog modal-lg">
            <div class="modal-content borda-modal">
              <div class="modal-body rounded-4 text-center">
                <img class="img-fluid mx-auto rounded-4" src="images/img3.png" alt="certificado-1">

                <button type="button" class="buttonClass font-style-title mt-3 rounded-4">
                  <a href="https://theocritean-specifi.000webhostapp.com/" target="_blank" title="Visitar projeto" class="font-color-title">
                    <i class="fa-regular fa-file" /> Ver projeto
                  </a>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
