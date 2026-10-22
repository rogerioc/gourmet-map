# 🗺️ Gourmet Map BH

Um mapa interativo completo, rápido, elegante e responsivo com curadoria gastronômica, festivais temporários e benefícios para Belo Horizonte e região (com suporte estendido a São Paulo).

👉 **Acesse o mapa ao vivo:** [rogerioc.github.io/gourmet-map](https://rogerioc.github.io/gourmet-map/)

---

## ✨ O que há de novo (Edição Gourmet Map BH)

- **🎨 Nova Identidade Visual Clara (Warm Light Gourmet)**:
  - Layout moderno, luminoso e editorial, com vidro fosco translúcido (*Glassmorphism* claro) e tipografia Outfit de alta legibilidade.
  - Marcadores de mapa e popups redesenhados para leitura rápida tanto em desktop quanto sob luz do dia no celular.
  - Nova opção de mapa base **CartoDB Clean (Voyager)** além de Google Maps Standard e Satélite.

- **🍷 Integração Oficial com o Festival Restaurant Week BH**:
  - Dados completos dos restaurantes participantes da 30ª edição do Belo Horizonte Restaurant Week.
  - Card exclusivo no popup com faixas de preço promocionais para Almoço e Jantar.
  - Menus completos sanfonados com Entrada, Prato Principal e Sobremesa.
  - Botão com link direto para a página oficial do restaurante no portal Restaurant Week (`https://eventos.restaurantweek.com.br/belohorizonte/restaurante/...`).

- **⚡ Chips de Filtro Rápido por Circuito / Festival**:
  - **`Todos`**: Visão global de todos os estabelecimentos cadastrados.
  - **`Duo Gourmet`**: Restaurantes com o benefício "peça 2 pratos e pague 1".
  - **`Restaurant Week`**: Restaurantes participantes do festival temporário.
  - **`Duo + Week`**: Restaurantes que participam **simultaneamente de ambos**, permitindo escolher entre o benefício Duo ou o menu fechado do Week.

---

## 🚀 Funcionalidades Principais

- **Filtros por Culinária**: Navegue por culinárias (Italiana, Hamburgueria, Japonesa, Brasileira, Carnes, Contemporânea, Bistrô, etc.).
- **Filtros por Localidade**:
  - Seleção de cidades (Belo Horizonte, Nova Lima, Contagem, Betim e São Paulo).
  - Dropdown inteligente de bairros que se atualiza automaticamente conforme a cidade selecionada.
- **Busca por Horário de Funcionamento**:
  - Filtre por dia da semana (`Hoje`, `Segunda`, etc.) e período (`Almoço` / `Jantar`).
  - Filtre por janela de horário específica (ex: de `19:30` às `22:00`), com tratamento de funcionamento em madrugadas.
- **Informações Ricas no Popup**:
  - Avaliação interna e nota do **Google Maps** com contagem de reviews.
  - Resumo editorial do Google e faixa de preço (`$` a `$$$$`).
  - Endereço, telefone, Instagram e site oficial com rastreamento anônimo de cliques.
  - Tabela completa de horários de almoço e jantar com destaque do dia atual.
  - Botões de rota rápida no Google Maps e link para a página oficial do benefício.
- **Design Totalmente Responsivo**:
  - **Desktop**: Layout elegante com lista lateral e mapa em tela cheia.
  - **Mobile**: Gaveta deslizante inteligente (*off-canvas*) que recolhe ao tocar no card para dar visibilidade total ao mapa.

---

## 🛠️ Tecnologias Utilizadas

- **Leaflet.js & MarkerCluster**: Motor de renderização e agrupamento inteligente de mapas.
- **CartoDB & Google Maps Tiles**: Camadas de mapa vetoriais e de satélite.
- **FontAwesome 6 & Google Fonts (Outfit)**: Iconografia e tipografia gastronômica.
- **Vanilla Modern CSS & JavaScript**: Interface rápida, responsiva e fluida sem dependências pesadas de frontend.
- **Playwright (Python)**: Suíte completa de testes automatizados End-to-End (E2E) para validação de filtros, rotas, popups e responsividade.
- **Firebase SDK**: Analytics de engajamento com respeito total à LGPD e banner de consentimento de cookies.

---

## ✒️ Autor & Créditos

- Desenvolvido por [Rogerio C.S](https://rogerioc.github.io/about/).
- Desenvolvido em pair programming com IA usando **Antigravity (Google DeepMind)**.
- Dados e marcas: [Duo Gourmet](https://www.duogourmet.com.br) & [Restaurant Week Brasil](https://restaurantweek.com.br).
