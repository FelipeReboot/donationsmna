<script>
    import SecWrap from "./SecWrap.svelte";
</script>

<SecWrap id="Pagina">
    <section>
        <div class="flex items-center justify-center min-h-screen bg-gray-100 p-5">
          <div class="max-w-4xl flex flex-col lg:flex-row items-center lg:items-start">
            <!-- Imagem -->
            <img
              src="/assets/qrcode.png"
              alt="QR code para doações"
              class="w-1/3 lg:w-1/4 rounded-lg shadow-lg mb-6 lg:mb-0"
            />
      
            <!-- Texto ao lado -->
            <div class="lg:ml-8 text-center lg:text-left">
              <h1 class="text-2xl lg:text-3xl font-bold text-gray-800">
                Contribua com o nosso trabalho
              </h1>
              <p class="mt-4 text-gray-600">
                Você pode doar através do <strong>Código QR</strong>, <strong>Pix</strong> ou <strong>depósito bancário</strong>.<br>
                <strong>Chave Pix:</strong> 14.796.743/0001-24<br>
                <strong>Banco Itaú:</strong> Agência 4020, Conta 351708
              </p>
              <p class="mt-4 text-gray-600">
                Caso deseje que sua doação tenha um destino específico, como o <strong>projeto Levando Amor</strong> ou <strong>Missões</strong>, 
                por favor, especifique através de <strong>e-mail</strong>, <strong>WhatsApp</strong> ou no <strong>comentário do Pix</strong>.<br>
                <strong><i class="fa-solid fa-envelope"></i> E-mail:</strong> ministerionova@hotmail.com<br>
                <strong><i class="fa-brands fa-whatsapp"></i> WhatsApp:</strong> (41)9 9955-7309
              </p>
              
            </div>
          </div>
        </div>
      </section>
      
    
</SecWrap>
