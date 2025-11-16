# Desafio: Montar uma tela BB
Dificuldade: Iniciante

1. FOI CRIADO SOMENTE A PARTE VISUAL E BEM BASICO DO SITE DO BANDO DO BRASIL.
2. NÃO TEM FUNCIONALIDADE NENHUMA.
3. EXERCICIO DO CURSO DIGITAL COLLEGE.

<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css"
        integrity="sha512-2SwdPD6INVrV/lHTZbO2nodKhrnDdJK9/kg2XD1r9uGqPo1cUbujc+IYdlYdEErWNu69gVcYgdxlmVmzTWnetw=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Banco do Brasil</title>
</head>

<body>
    <header class="flex justify-between bg-[#FFF22D]">
        <section class=" w-full h-[70px] flex items-center gap-3">
            <i class="fa-solid fa-bars ml-3 text-[#465EFF] cursor-pointer"></i>
            <img src="https://assets.hgbrasil.com/finance/companies/big/banco-do-brasil.png"
                class="w-[50px] border-r-1 border-gray-400 cursor-pointer" alt="logo">

            <select id="Pra você" name="pra você" class="text-[#466DC6] ml-1 text-xl font-bold cursor-pointer">
                <option value="pra você">Pra você</option>
                <option value="Inicio">Inicio</option>
                <option value="Contas">Contas</option>
            </select>
            <select id="Pro seu negocio" name="Pro seu negocio" class="text-[#466DC6] ml-1 text-xl font-bold cursor-pointer">
                <option value="Pro seu negocio">Pro seu negócio</option>
                <option value="Contas">Inicio</option>
                <option value="Contas">Contas</option>
            </select>
            <select id="Agronegócios" name="Agronegócios" class="text-[#466DC6] ml-1 text-xl font-bold cursor-pointer">
                <option value="Pro seu negocio">Agronegócios</option>
                <option value="Contas">Custeio</option>
                <option value="Contas">Investimentos</option>
            </select>
            <select id="Setor Público" name="Setor Público" class="text-[#466DC6] ml-1 text-xl font-bold cursor-pointer">
                <option value="Setor Público">Setor Público</option>
                <option value="Contas">Inicio</option>
                <option value="Contas">Federal</option>
            </select>
            <section
                class="flex items-center border border-gray-300 bg-[#CDCE54] w-[350px] h-[50px] ml-2 p-1 rounded-sm ">
                <i class="fa-solid fa-magnifying-glass mr-2 text-white"></i>
                <input type="text" placeholder="O que você procura?"
                    class="text-white placeholder:text-white outline-0 placeholder:font-bold placeholder:text-lg placeholder:w-[300px] w-full">
            </section>
        </section>
        <section class="flex items-center mr-4 text-xl font-bold text-[#466DC6] hover:bg-[#B0B022]">
            <select name="" id="" class="cursor-pointer">
                <option value="">ACESSE A SUA CONTA </option>
            </select>
        </section>
    </header>
    <div class="w-full h-[70px] bg-blue-700 flex items-center">
<section class="flex items-center">
    <i class="fa-solid fa-house text-2xl text-[#FFF22D] ml-30 cursor-pointer"></i>
    <p class="ml-2 text-xl font-bold text-[#FFF22D] cursor-pointer">Investimentos</p>
    <p class="ml-2 text-xl font-bold text-gray-300">/ CDB</p>
</section>
    </div>
    <main class=" flex w-full h-screen bg-[url('https://imgix.bustle.com/uploads/getty/2022/10/3/5de98767-d65e-4792-9129-35da57293868-getty-1428693472.jpg')] bg-cover bg-center min-h-screen">
        <section class="flex flex-col text-left pl-60 pt-40 gap-3">
            <h1 class="text-7xl font-bold text-[#FFF22D]">CDB</h1>
            <p class="text-white w-[450px] text-2xl">Pra você que busca um investimento seguro e que possa ser resgatado a qualquer
       hora, com o Certificado de Depósito Bancário (CDB), você investe seu dinheiro com
       remuneração diária.</p>
       <button class="bg-[#FFF22D] h-[60px] w-[250px] flex items-center justify-center rounded-sm text-xl font-bold text-[#466DC6] mt-12 cursor-pointer">INVESTIR AGORA</button>
       <div class="flex gap-2 mt-50 items-center">
       <section class="bg-white w-[250px] h-[150px] flex flex-col rounded-md justify-center items-center">
<p class="text-3xl font-bold text-[#466DC6]">Pré e Pós</p>
<p class="text-md font-bold text-[#466DC6]">Modalidades</p>
<p class="text-md font-bold text-[#466DC6]">Disponíveis</p>
       </section>
       <section class="bg-white w-[250px] h-[150px] flex flex-col rounded-md justify-center items-center">
<i class="fa-solid fa-battery-full text-5xl text-[#466DC6] mb-2"></i>
<p class="text-md font-bold text-[#466DC6]">Risco</p>
<p class="text-md font-bold text-[#466DC6]">Muito baixos</p>
       </section>
       <section class="bg-white w-[250px] h-[150px] flex flex-col rounded-md justify-center items-center">
<i class="fa-solid fa-dollar-sign text-5xl text-[#466DC6] mb-2"></i>
<p class="text-md font-bold text-[#466DC6]">Aplicações a</p>
<p class="text-md font-bold text-[#466DC6]">partir de R$0,01</p>
       </section>
       <section class="bg-white w-[250px] h-[150px] flex flex-col rounded-md justify-center items-center">
<i class="fa-regular fa-calendar text-5xl text-[#466DC6] mb-2"></i>
<p class="text-md font-bold text-[#466DC6]">Diversas opções</p>
<p class="text-md font-bold text-[#466DC6]">de liquidez</p>
       </section>
       <section class="bg-[#5BF573] rounded-4xl h-[60px] text-center justify-center flex ml-140 cursor-pointer">
        <i class="fa-brands fa-whatsapp text-5xl text-white pt-1"></i>
       </section>
       </div>
        </section>
    </main>
</body>

</html>
