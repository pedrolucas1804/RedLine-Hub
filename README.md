RedLine Hub — Catálogo de Supercarros (PWA)
Aplicação web progressiva (PWA) mobile-first para exploração de um catálogo curado com 17 modelos das 8 marcas mais icônicas do automobilismo de alto desempenho: Ferrari, Lamborghini, Porsche, McLaren, Bugatti, Aston Martin, Maserati e Koenigsegg.
Funcionalidades principais:

Catálogo completo com foto, descrição detalhada e especificações técnicas de cada modelo
Filtro por marca com chips deslizantes animados
Busca em tempo real com animação visual de feedback
Modal de detalhes com swipe para fechar (gesto nativo mobile)
Câmera integrada com suporte a câmera frontal/traseira, captura de foto e feedback háptico via vibração
Header com comportamento inteligente de ocultação no scroll

Tecnologias e padrões:

HTML5, CSS3 e JavaScript puro — sem frameworks ou dependências externas
PWA completo com Service Worker para cache offline e manifest para instalação na tela inicial
Design system com variáveis CSS, tipografia editorial e paleta luxury dark
Animações CSS com respeito a prefers-reduced-motion
Semântica acessível com atributos ARIA, navegação por teclado e foco gerenciado
API getUserMedia para acesso à câmera do dispositivo
API navigator.vibrate para feedback háptico na captura de foto

Critérios de qualidade (Lighthouse):

Performance otimizada com loading="lazy" nas imagens, animações via transform (GPU) e assets cacheados pelo Service Worker
Acessibilidade com contraste elevado, roles semânticos e live regions
PWA instalável com manifest completo, ícones e suporte offline
Boas práticas com viewport correto, meta descriptions e HTTPS-ready
