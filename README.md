# Hi-Tech | Tecnologia & Soluções

Site institucional/portfólio desenvolvido para apresentar conteúdos, serviços e materiais voltados à área de Tecnologia da Informação.

O projeto foi estruturado como um site estático para publicação no **GitHub Pages**, utilizando apenas **HTML, CSS e JavaScript**, sem necessidade de backend ou banco de dados.

## Visão geral

A proposta do site é reunir, em uma única página pública e profissional, informações sobre:

- Softwares e ferramentas de TI;
- Tutoriais e cursos;
- eBooks técnicos;
- Portfólio profissional;
- Experiência na área de infraestrutura, redes e suporte;
- Canais de contato.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- jQuery
- ScrollReveal
- Font Awesome
- Google Fonts
- GitHub Pages

## Estrutura principal

```text
/
├── index.html
├── softwares.html
├── tutoriais.html
├── ebooks.html
├── portfolio.html
├── shared.css
├── README.md
├── wave.svg
└── src/
    └── images/
```

## Páginas do projeto

### `index.html`

Página inicial do site. Contém o hero principal, apresentação da marca Hi-Tech, produtos em destaque, seção Sobre Mim e contatos.

### `softwares.html`

Página dedicada aos softwares, ferramentas e soluções que podem ser instaladas, configuradas ou recomendadas em ambientes de TI.

### `tutoriais.html`

Página voltada para tutoriais, mini-cursos e cursos completos sobre Windows, Linux, redes, servidores e infraestrutura.

### `ebooks.html`

Página exclusiva para a biblioteca de eBooks, com cards de materiais técnicos, descrição, preço, quantidade de páginas e botão de compra.

### `portfolio.html`

Página com projetos, experiências e competências técnicas, destacando atuação em infraestrutura, redes, automação, aplicações web e TI na saúde.

### `shared.css`

Arquivo de estilos compartilhado entre as páginas internas, responsável por manter o padrão visual do site.

## Mudanças recentes

- Padronização visual das páginas internas com base no estilo da página inicial.
- Criação e organização do arquivo `shared.css`.
- Correção da página `ebooks.html`, que agora possui conteúdo próprio.
- Ajuste dos links de navegação entre as páginas.
- Atualização da seção **Sobre Mim** com a linha do tempo profissional e acadêmica:
  - 2014.2 a 2017.2 — início da vida acadêmica em Redes de Computadores;
  - 2017 a 2022 — primeira experiência profissional em TI, iniciando como estagiário e evoluindo para técnico;
  - 2022 a 2024 — início da experiência como analista;
  - 2024 a 2026 — continuidade como analista, ganhando mais experiência;
  - 2026 — atuação como analista e criador de conteúdo.
- Remoção do card de TikTok da área de contato.
- Remoção dos cards de comentários/depoimentos.
- Melhoria nos efeitos de hover dos cards, deixando a interação mais visível e profissional.
- Ajustes gerais de responsividade para melhor exibição em desktop e mobile.

## Publicação

O projeto foi preparado para rodar no **GitHub Pages**.

Para publicar, basta manter os arquivos na raiz do repositório e configurar o GitHub Pages para usar:

```text
Source: Deploy from a branch
Branch: main
Folder: /root
```

Após salvar a configuração e enviar os arquivos para a branch `main`, o site será publicado automaticamente.

## Observações importantes

Este é um site estático. Portanto, todos os arquivos HTML, CSS, JavaScript e imagens ficam públicos quando publicados no GitHub Pages.

Não inclua no projeto:

- Senhas;
- Tokens;
- Chaves de API;
- Dados internos;
- Planilhas privadas;
- Arquivos sensíveis;
- Credenciais de plataformas de pagamento.

## Autor

Projeto criado e personalizado para a marca **Hi-Tech**, com foco em tecnologia, infraestrutura, redes, suporte técnico, tutoriais, eBooks e soluções para profissionais e entusiastas de TI
