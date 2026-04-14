# Snitap Patins

Landing page de apresentação para a marca Snitap, criada com HTML e CSS.

<img width="1905" height="1079" alt="image" src="https://github.com/user-attachments/assets/427a4dc0-4267-4949-89eb-bc1d0eeaa9cf" />

## Sobre o projeto

Este projeto exibe uma página de produto com visual moderno, animações e transições focadas em experiência de usuário. O layout conta com seção hero, banner de rolagem, galeria de imagens e rodapé.

## Principais características

- Animação de texto principal com palavras que deslizam no `hero`
- Transições de hover nos botões e imagens
- Animação de entrada dos elementos do patins e dos ícones de estrela
- Banner animado com rolagem contínua e gradiente em movimento
- Galeria com efeito de aparecer ao scroll e revelação de legenda ao passar o mouse
- Uso de fontes do Google Fonts e imagens vetoriais/PNG para reforçar o estilo visual

## Arquivos importantes

- `index.html` - estrutura principal da página
- `styles/index.css` - importa todos os estilos do projeto
- `styles/global.css` - estilo base e variáveis de cores
- `styles/header.css` - estilo do cabeçalho
- `styles/hero.css` - animações, transições e layout do hero
- `styles/banner.css` - animação do banner rolante
- `styles/gallery.css` - galeria de fotos com hover e scroll animation
- `styles/footer.css` - estilo do rodapé

## Animações e interações

- Botões com `transition: scale` para zoom suave ao passar o mouse
- Elementos do `hero` com `@keyframes slideIn` e `@keyframes appear`
- Texto do título com animação cíclica `slideUp` para alternar palavras
- Banner com animação `rolling` para efeito infinito de scroll horizontal
- Galeria com animação de entrada via `animation-timeline: view()` e hover nas imagens

## Como usar

1. Abra o arquivo `index.html` em um navegador.
2. Verifique se a pasta `assets` está no mesmo nível que o HTML.
3. Navegue pelas seções para ver as animações em ação.

## Observações

O projeto foi feito com foco em animações CSS puras, sem JavaScript, entregando uma experiência interativa e suave apenas com HTML e CSS.
