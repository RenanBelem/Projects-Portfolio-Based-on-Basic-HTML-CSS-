## Portfolio de Projetos (Modelo Básico)

Este é um projeto de *landing page* ou portfólio básico, focando em listar e fornecer acesso rápido a outros projetos.

### Estrutura do Projeto

O projeto é composto por dois arquivos principais:

1.  **`index.html`**: Estrutura básica HTML que define o conteúdo da página.
2.  **`index.css`**: Arquivo de estilo CSS para a apresentação visual.

### Conteúdo Principal

A página é intitulada **"Portfolio Renan"** e lista projetos sob o subtítulo **"Projetos de sala"**.

#### Seções da Página
* **Descrição:** Contém o nome do autor (**"Renan Belem Biavati"**) e o subtítulo da seção.
* **Cards:** Apresenta botões clicáveis, cada um representando um projeto.

#### Projetos Listados
1.  **Arthur's Redemption:** Um link para abrir o jogo em uma nova aba (`target="_blank"`).
    * **Título do Card:** "Arthur's Redemption".
    * **Subtítulo do Card:** "Abrir Jogo".
2.  **Galeria de artes:** Um link para baixar o projeto do GitHub.
    * **Título do Card:** "Galeria de artes".
    * **Subtítulo do Card:** "Baixar projeto".

### Estilo e Design (`index.css`)

O design foca em um esquema de cores simples com um fundo ciano vibrante e elementos em branco e roxo.

* **Fundo (`body`):** Cor ciano (`#0fcbd8`).
* **Tipografia:**
    * **Nome:** Tamanho de 35px, em negrito, cor branca (`#ffffff`).
    * **Subtítulo Principal:** Tamanho grande (85px), cor branca, em negrito.
* **Cards (Botões de Projeto):**
    * **Estilo:** Botões grandes, com dimensões fixas de 500px por 275px, com margens e um `box-shadow`.
    * **Formato:** Borda arredondada (50% de `border-radius`), dando-lhes uma forma circular ou oval.
    * **Cores:** Borda na cor roxa (`#a412b8`).
    * **Efeito Hover:** Ao passar o mouse, o fundo do botão se torna preto (`#000000`).
    * **Títulos dos Cards:** Cor branca (`#fcf4f4`).
    * **Subtítulos dos Cards:** Cor roxa (`#bf10d6`) em negrito.

### Observações Técnicas

* O projeto referencia um script JavaScript (`js/index.js`) que não foi fornecido.
* O layout dos cartões é organizado em linhas (`cards-top`, `cards-bottom`) usando **Flexbox**.
