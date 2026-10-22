# Site Frattini Labs

Site estático, sem build: é só HTML, CSS e JS puros. Pra hospedar, basta publicar esta pasta inteira como está (Vercel, Netlify, GitHub Pages, Cloudflare Pages etc.). Não tem `npm install` nem passo de compilação.

## Estrutura
- `index.html`: a página inteira (estilos e scripts estão dentro dela)
- `assets/img/`: imagens da arara em .webp, já otimizadas
- `assets/fonts/`: fontes locais (Rubik Spray Paint, Archivo Black, Archivo)
- `vendor/`: GSAP, ScrollTrigger e Lenis (animações e rolagem suave), copiados localmente

## Configurações
- O WhatsApp do botão está na constante `WPP` no fim do `index.html`: wa.me/5582988224653, já com uma mensagem pronta.
- Instagram no rodapé: @frattinilabs

## Ao hospedar
- Diretório raiz = esta pasta. Comando de build: nenhum. Pasta de saída: `.` (a própria raiz).
- Os originais das imagens (PNG) ficam fora daqui, em `02 - Identidade Visual/Imagens do site (originais)`, e não devem ser publicados.
