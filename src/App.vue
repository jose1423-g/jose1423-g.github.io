<template>
  
<div class="min-h-screen">
  <div class="container px-5 mx-auto text-sm">
    <div class="flex justify-center">

      <div class="flex mt-[4rem]">

        <div class="w-[585px] hidden lg:block">
          <img src="/img/instagram-web.png" alt="" class="h-[450px] mt-[3rem]">
        </div>

        <div class="w-[21.875rem]">

          <div class="flex justify-center">
              <img src="/img/logo-instagram.png" alt="" class="w-[175px] h-[51px] mt-[36px] mb-[12px]">
          </div>

          <form action="" method="post" class="mt-[24px] px-3">
              <div class="grid grid-cols-1 gap-2">
                <input type="text" class="bg-[#fafafa] px-[8px] py-[9px] w-full border border-[#e4e4e4] rounded-sm focus:outline focus:outline-[#e4e4e4]" placeholder="Teléfono, usuario o correo electronico">

                <div class="flex justify-between bg-[#fafafa] px-2 py-2 w-full border border-[#e4e4e4] rounded-sm focus:outline focus:outline-[#e4e4e4]">
                  <input type="text" class="focus:outline-0" placeholder="Contraseña">
                  <button type="button" class="cursor-pointer">
                    Mostrar
                  </button>
                </div>
                
                <button type="button" class="cursor-pointer bg-[#4eb3f7] my-[8px] rounded-md h-[32px] font-semibold text-white">
                  Iniciar Sesión
                </button>
              </div>
          </form>

          <div class="flex items-center gap-2 my-[2rem]">
              <div class="flex-1 border-t border-gray-300"></div>
              <div class="mx-3 text-gray-600">O</div>
              <div class="flex-1 border-t border-gray-300"></div>
          </div>

          <div class="text-center mb-[2rem]">

              <a href="/" class="flex justify-center items-center mb-3">
                  <img src="/img/facebook.png" alt="" class="size-6 mr-2">
                  <span class="text-[#0095f7] font-semibold">Iniciar sesión con facebook</span>
              </a>
              <a href="/" class="text-gray-500">                  
                ¿Olvidaste tu contraseña?
              </a>
          </div>

          <div class="text-center mb-[2rem]">
              <a href="" class="">¿ No tienes una cuenta ?<span class="text-[#0095f7] font-semibold ml-2">Regístrate</span></a>
          </div>

          <div class="text-center">
              <span class=" mb-[5rem]">Descarga la app.</span>
              <div class="flex justify-center gap-1 mt-4">
                  <img src="/img/playstore.png" alt="" class="w-[134px] h-[40px]">
                  <img src="/img/microsoft.png" alt="" class="w-[110px] h-[40px]">
              </div>
          </div>

        </div>       

      </div>

    </div>

    <footer class="flex flex-col items-center text-gray-500 text-sm space-y-2 py-1 mt-10">
      <div class="flex flex-wrap justify-center gap-4">
          <a href="#" class="hover:underline">Meta</a>
          <a href="#" class="hover:underline">Información</a>
          <a href="#" class="hover:underline">Blog</a>
          <a href="#" class="hover:underline">Empleo</a>
          <a href="#" class="hover:underline">Ayuda</a>
          <a href="#" class="hover:underline">API</a>
          <a href="#" class="hover:underline">Privacidad</a>
          <a href="#" class="hover:underline">Condiciones</a>
          <a href="#" class="hover:underline">Ubicaciones</a>
          <a href="#" class="hover:underline">Instagram Lite</a>
          <a href="#" class="hover:underline">Threads</a>
          <a href="#" class="hover:underline">Importación de contactos y no usuarios</a>
          <a href="#" class="hover:underline">Meta Verified</a>
      </div>

      <div class="flex items-center gap-2">
          <span>Español</span>
          <span>© 2025 Instagram from Meta</span>
      </div>
    </footer>

  </div>
</div>

 

</template>
