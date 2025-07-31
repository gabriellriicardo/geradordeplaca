# Gerador de Placas Hortifruti 🍎🛒

Este é um projeto frontend simples, construído com **HTML, CSS (Tailwind) e JavaScript puro**, que cria uma ferramenta web para gerar placas de preços para produtos de hortifruti. A aplicação permite carregar uma lista de produtos a partir de um arquivo de texto, selecionar os itens desejados, personalizar uma imagem de cabeçalho e gerar folhas no formato A4, prontas para impressão.

-----

## ✨ Funcionalidades

  * **Carregamento de Dados Dinâmico**:

      * Carrega uma lista de produtos de um arquivo `TXITENS.txt`.
      * Carrega uma imagem de cabeçalho (`hortifrut.jpeg`) para as placas.
      * Permite que o usuário **faça o upload de seus próprios arquivos** para substituir os padrões.

  * **Interface Interativa**:

      * **Busca em tempo real** para filtrar produtos por nome ou código.
      * Visualização de produtos em duas abas: "Todos" e "Selecionados".
      * **Seleção múltipla** de produtos para geração em lote.
      * Botão para "Desmarcar Todos" com um único clique.

  * **Edição e Pré-visualização**:

      * **Pré-visualização individual** de como a placa de um produto ficará.
      * **Edição embutida**: Altere a descrição, preço, unidade e código de um produto diretamente na interface.

  * **Geração e Impressão**:

      * Gera as imagens das placas usando a **API Canvas** do HTML5 para alta qualidade.
      * Agrupa automaticamente **duas placas por folha A4**, otimizando o papel.
      * Exibe uma **área de pré-visualização** com as folhas A4 geradas.
      * Função de **impressão** que formata a página corretamente, escondendo a interface e mostrando apenas as folhas a serem impressas.
      * Opção para **salvar as placas individualmente** como arquivos `.png`.

-----

## 🚀 Como Usar

1.  **Abra o `index.html`**: A maneira mais simples de usar é abrir o arquivo `index.html` em seu navegador.
2.  **Carregue seus arquivos (Opcional)**:
      * A aplicação já carrega um arquivo `TXITENS.txt` e uma imagem `hortifrut.jpeg` como padrão.
      * Se desejar, clique nos campos de upload para selecionar seus próprios arquivos.
3.  **Pesquise e Selecione os Produtos**:
      * Use a barra de pesquisa para encontrar produtos específicos.
      * Clique no ícone de checkbox (🔲) para selecionar os produtos que deseja imprimir.
4.  **Edite se Necessário**:
      * Clique no botão **"Ver"** ao lado de um produto para abrir a pré-visualização.
      * Na janela de pré-visualização, clique em **"Editar"** para modificar as informações do produto.
5.  **Gere as Folhas**:
      * Após selecionar todos os produtos, clique no botão **"Gerar Folhas para Impressão"**.
      * Aguarde a barra de progresso ser concluída. A área de pré-visualização abaixo mostrará as folhas A4 prontas.
6.  **Imprima**:
      * Clique no botão **"Imprimir Folhas Geradas"** para abrir a caixa de diálogo de impressão do seu navegador.

-----

## 📂 Estrutura de Arquivos

```
/
├── .nojekyll           # Necessário para o deploy correto no GitHub Pages
├── hortifrut.jpeg      # Imagem de cabeçalho padrão para as placas
├── Impact.ttf          # Arquivo da fonte 'Impact' usada nas placas
├── index.html          # O coração da aplicação (HTML, CSS e JavaScript)
├── TXITENS.txt         # Lista de produtos padrão com código, preço e descrição
└── README.md           # Este arquivo
```

-----

## 🛠️ Tecnologias Utilizadas

  * **HTML5**: Estrutura da página.
  * **CSS3**: Estilização e responsividade.
  * **[Tailwind CSS](https://tailwindcss.com/)**: Framework CSS para agilizar o desenvolvimento da UI.
  * **JavaScript (ES6+)**: Lógica da aplicação, manipulação do DOM e interatividade.
  * **HTML Canvas**: Para a geração dinâmica das imagens das placas.

-----

## ✍️ Autor

  * **Gabriel Ricardo** - [GitHub](https://github.com/gabriellriicardo)
