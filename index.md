<html lang="pt">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Braga 2026 - Capital Europeia do Turismo Inteligente</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primary: '#2563eb',
            secondary: '#0f172a'
          },
          borderRadius: {
            'none': '0px',
            'sm': '4px',
            DEFAULT: '8px',
            'md': '12px',
            'lg': '16px',
            'xl': '20px',
            '2xl': '24px',
            '3xl': '32px',
            'full': '9999px',
            'button': '8px'
          }
        }
      }
    }
  </script>
  <style>
    :where([class^="ri-"])::before {
      content: "\f3c2";
    }

    .hero-gradient {
      background: linear-gradient(90deg, rgba(255, 255, 255, 1) 0%, rgba(255, 255, 255, 0.9) 50%, rgba(255, 255, 255, 0) 100%);
    }
  </style>
</head>

<body class="bg-white">
  <header class="fixed w-full bg-white/95 backdrop-blur-sm z-50 shadow-sm">
    <nav class="container mx-auto px-6 py-4">
      <div class="flex items-center justify-between">
        <div class="flex items-center gap-12">
          <a href="#" class="flex items-center">
            <img src="https://scontent-lis1-1.xx.fbcdn.net/v/t39.30808-6/474819051_1080705040764437_7163864804145433871_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=KlEZB0uCtWcQ7kNvgH4QKPt&_nc_oc=Adkyg51hHDYS5GT9qv6SKoGAsx7PeVs1uCSUI91Hf-NUml8bOaRkrF7cm_z6SGGO5H0&_nc_zt=23&_nc_ht=scontent-lis1-1.xx&_nc_gid=lilrb0sHzPvT7g3koMsdgA&oh=00_AYF4yv5Ak3b68hfefVY0ldJYETN2dguPnTd5h2j8ADYubw&oe=67E714EA" alt="Braga 2026" class="h-12">
          </a>
          <div class="hidden md:flex items-center gap-8">
            <a href="#inicio" class="text-gray-600 hover:text-primary">Início</a>
            <a href="#sobre" class="text-gray-600 hover:text-primary">Sobre</a>
            <a href="#patrimonio" class="text-gray-600 hover:text-primary">Património</a>
            <a href="#sustentabilidade" class="text-gray-600 hover:text-primary">Sustentabilidade</a>
            <a href="#inovacao" class="text-gray-600 hover:text-primary">Inovação</a>
            <a href="#cultura" class="text-gray-600 hover:text-primary">Cultura</a>
          </div>
        </div>
        <button class="bg-primary text-white px-6 py-2 !rounded-button hover:bg-primary/90">Apoiar Candidatura</button>
      </div>
    </nav>
  </header>
  <main>
    <section id="inicio" class="relative min-h-screen flex items-center" style="background-image: url('https://www.impulsiveaddiction.com/wp-content/uploads/2021/09/bom-jesus-de-braga-3.jpg'); background-size: cover; background-position: center;">
      <div class="absolute inset-0 hero-gradient"></div>
      <div class="container mx-auto px-6 relative">
        <div class="max-w-2xl">
          <h1 class="text-5xl font-bold mb-6 font-['Playfair_Display']">Braga: Capital Europeia do Turismo Inteligente 2026</h1>
          <p class="text-xl mb-8">Onde o património milenar encontra a inovação do futuro. Uma cidade que respira história e pulsa tecnologia.</p>
          <button class="bg-primary text-white px-8 py-3 !rounded-button hover:bg-primary/90">Conheça Nossa Candidatura</button>
        </div>
      </div>
    </section>
    <section id="numeros" class="py-20 bg-gray-50">
      <div class="container mx-auto px-6">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="bg-white p-8 rounded-lg shadow-sm text-center">
            <div class="text-4xl font-bold text-primary mb-2">275.000+</div>
            <div class="text-gray-600">Hóspedes em 2024</div>
          </div>
          <div class="bg-white p-8 rounded-lg shadow-sm text-center">
            <div class="text-4xl font-bold text-primary mb-2">€39M</div>
            <div class="text-gray-600">Receitas Turísticas</div>
          </div>
          <div class="bg-white p-8 rounded-lg shadow-sm text-center">
            <div class="text-4xl font-bold text-primary mb-2">#1</div>
            <div class="text-gray-600">Melhor Destino Emergente da Europa</div>
          </div>
        </div>
      </div>
    </section>
    <section id="patrimonio" class="py-20">
      <div class="container mx-auto px-6">
        <h2 class="text-4xl font-['Playfair_Display'] font-bold mb-12 text-center">Património Cultural</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="bg-white rounded-lg overflow-hidden shadow-sm">
            <img src="https://cms-files.carlomonteiro.pt/CARLOMONTEIRO_images/2019/07/10/1024_720/PT__20190710103031_1410818407.jpeg" class="w-full h-48 object-cover" alt="Bom Jesus do Monte">
            <div class="p-6">
              <h3 class="text-xl font-bold mb-2">Bom Jesus do Monte</h3>
              <p class="text-gray-600 mb-4">Património Mundial da UNESCO, um exemplo único de arquitetura barroca e local de peregrinação.</p>
              <button class="text-primary flex items-center gap-2 hover:underline">
                Tour Virtual <i class="ri-arrow-right-line"></i>
              </button>
            </div>
          </div>
          <div class="bg-white rounded-lg overflow-hidden shadow-sm">
            <img src="https://se-braga.pt/wp-content/themes/yootheme/cache/48/img_7412-48b5556b.jpeg" class="w-full h-48 object-cover" alt="Sé Catedral">
            <div class="p-6">
              <h3 class="text-xl font-bold mb-2">Sé Catedral</h3>
              <p class="text-gray-600 mb-4">A mais antiga catedral de Portugal, símbolo da história religiosa e cultural de Braga.</p>
              <button class="text-primary flex items-center gap-2 hover:underline">
                Tour Virtual <i class="ri-arrow-right-line"></i>
              </button>
            </div>
          </div>
          <div class="bg-white rounded-lg overflow-hidden shadow-sm">
            <img src="https://upload.wikimedia.org/wikipedia/commons/3/30/Termas_de_Maximinos.JPG" class="w-full h-48 object-cover" alt="Ruínas Romanas">
            <div class="p-6">
              <h3 class="text-xl font-bold mb-2">Ruínas Romanas das Carvalheiras</h3>
              <p class="text-gray-600 mb-4">Vestígios da antiga Bracara Augusta, testemunho da presença romana em Braga.</p>
              <button class="text-primary flex items-center gap-2 hover:underline">
                Tour Virtual <i class="ri-arrow-right-line"></i>
              </button>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="inovacao" class="py-20 bg-gray-50">
      <div class="container mx-auto px-6">
        <h2 class="text-4xl font-['Playfair_Display'] font-bold mb-12 text-center">Inovação e Sustentabilidade</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
          <div class="bg-white p-8 rounded-lg shadow-sm">
            <div class="flex items-start gap-4">
              <div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full">
                <i class="ri-bike-line text-primary text-2xl"></i>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-2">Mobilidade Sustentável</h3>
                <p class="text-gray-600">Rede de ciclovias, transportes públicos elétricos e zonas pedonais para uma cidade mais verde.</p>
              </div>
            </div>
          </div>
          <div class="bg-white p-8 rounded-lg shadow-sm">
            <div class="flex items-start gap-4">
              <div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full">
                <i class="ri-leaf-line text-primary text-2xl"></i>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-2">Green Destinations Platinum</h3>
                <p class="text-gray-600">Primeira cidade portuguesa com certificação máxima em sustentabilidade turística.</p>
              </div>
            </div>
          </div>
          <div class="bg-white p-8 rounded-lg shadow-sm">
            <div class="flex items-start gap-4">
              <div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full">
                <i class="ri-smartphone-line text-primary text-2xl"></i>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-2">Smart Tourism</h3>
                <p class="text-gray-600">Plataformas digitais inovadoras como TOMI e Smart-Guide para melhor experiência turística.</p>
              </div>
            </div>
            </div>
            <div class="bg-white p-8 rounded-lg shadow-sm">
            <div class="flex items-start gap-4">
              <div class="w-12 h-12 flex items-center justify-center bg-primary/10 rounded-full">
                <i class="ri-global-line text-primary text-2xl"></i>
              </div>
              <div>
                <h3 class="text-xl font-bold mb-2">Inclusão Digital</h3>
                <p class="text-gray-600">Acesso universal à informação turística através de tecnologias inclusivas.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
     </section>
     <img src="https://i.imgur.com/8VPCnpL.png" class="w-full h-48 object-cover" alt="Esquema">
    <section id="cultura" class="py-20">
      <div class="container mx-auto px-6">
        <h2 class="text-4xl font-['Playfair_Display'] font-bold mb-12 text-center">Cidade Criativa UNESCO</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="bg-white rounded-lg overflow-hidden shadow-sm">
            <img src="https://www.bragamediaarts.com/media/filer_public_thumbnails/filer_public/6a/65/6a65cc80-6bc2-4891-99e1-5fea2b10b477/221129_circuito_we_contar_historias_sem_palavras-35.jpg__2000x0_q85_subsampling-2_upscale.jpg" class="w-full h-48 object-cover" alt="Media Arts">
            <div class="p-6">
              <h3 class="text-xl font-bold mb-2">Media Arts</h3>
              <p class="text-gray-600">Reconhecimento UNESCO pela excelência em arte digital e tecnologia.</p>
            </div>
          </div>
          <div class="bg-white rounded-lg overflow-hidden shadow-sm">
            <img src="https://visitbraga.travel/welcome/pub/media/wysiwyg/Semana_Santa.jpg" class="w-full h-48 object-cover" alt="Eventos Culturais">
            <div class="p-6">
              <h3 class="text-xl font-bold mb-2">Eventos Culturais</h3>
              <p class="text-gray-600">Programação anual rica em eventos que fundem tradição e modernidade.</p>
            </div>
          </div>
          <div class="bg-white rounded-lg overflow-hidden shadow-sm">
            <img src="https://webraga.pt/wp-content/uploads/2025/01/we-braga-capital-portuguesa-cultura.jpg" class="w-full h-48 object-cover" alt="Inovação Cultural">
            <div class="p-6">
              <h3 class="text-xl font-bold mb-2">Inovação Cultural</h3>
              <p class="text-gray-600">Projetos que integram património histórico e tecnologia digital.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
  <footer class="bg-secondary text-white py-12">
    <div class="container mx-auto px-6">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
        <div>
          <img src="https://scontent-lis1-1.xx.fbcdn.net/v/t39.30808-6/474819051_1080705040764437_7163864804145433871_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=KlEZB0uCtWcQ7kNvgH4QKPt&_nc_oc=Adkyg51hHDYS5GT9qv6SKoGAsx7PeVs1uCSUI91Hf-NUml8bOaRkrF7cm_z6SGGO5H0&_nc_zt=23&_nc_ht=scontent-lis1-1.xx&_nc_gid=lilrb0sHzPvT7g3koMsdgA&oh=00_AYF4yv5Ak3b68hfefVY0ldJYETN2dguPnTd5h2j8ADYubw&oe=67E714EA" alt="Braga 2026" class="h-10 mb-4">
          <p class="text-gray-400">Capital Europeia do Turismo Inteligente</p>
        </div>
        <div>
          <h4 class="font-bold mb-4">Links Úteis</h4>
          <ul class="space-y-2">
            <li><a href="#" class="text-gray-400 hover:text-white">Sobre a Candidatura</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Agenda Cultural</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Mapa Turístico</a></li>
            <li><a href="#" class="text-gray-400 hover:text-white">Contactos</a></li>
          </ul>
        </div>
        <div>
          <h4 class="font-bold mb-4">Redes Sociais</h4>
          <div class="flex gap-4">
            <a href="#" class="w-10 h-10 flex items-center justify-center bg-white/10 rounded-full hover:bg-white/20">
              <i class="ri-facebook-fill"></i>
            </a>
            <a href="#" class="w-10 h-10 flex items-center justify-center bg-white/10 rounded-full hover:bg-white/20">
              <i class="ri-instagram-line"></i>
            </a>
            <a href="#" class="w-10 h-10 flex items-center justify-center bg-white/10 rounded-full hover:bg-white/20">
              <i class="ri-twitter-x-line"></i>
            </a>
          </div>
        </div>
        <div>
          <h4 class="font-bold mb-4">Newsletter</h4>
          <form class="flex gap-2">
            <input type="email" placeholder="Seu e-mail" class="bg-white/10 px-4 py-2 rounded-button flex-1 text-white placeholder-gray-400 border-none">
            <button type="submit" class="bg-primary px-4 py-2 !rounded-button hover:bg-primary/90">
              <i class="ri-send-plane-line"></i>
            </button>
          </form>
        </div>
      </div>
      <div class="border-t border-white/10 mt-12 pt-8 text-center text-gray-400">
        <p>&copy; 2025 Braga 2026. Todos os direitos reservados.</p>
      </div>
    </div>
  </footer>
  <script>
    document.addEventListener('DOMContentLoaded', function() {
      const header = document.querySelector('header');
      window.addEventListener('scroll', () => {
        if (window.scrollY > 50) {
          header.classList.add('shadow-md');
        } else {
          header.classList.remove('shadow-md');
        }
      });
    });
  </script>
</body>

</html>
