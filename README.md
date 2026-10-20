# 🔎 Sistema de Busca e Filtragem de Dados Policiais

Aplicação desktop desenvolvida em Python para facilitar a consulta, a visualização e a filtragem de registros armazenados em planilhas Excel, por meio de uma interface gráfica intuitiva.

O projeto foi desenvolvido originalmente no contexto de um trabalho acadêmico em grupo, com foco na criação de uma ferramenta para pesquisa de dados e aplicação de filtros combinados. Este repositório faz parte do meu portfólio, reunindo um projeto prático relacionado ao desenvolvimento de software e à manipulação de dados.

## 📌 Funcionalidades

- **Importação de planilhas:** carregamento de arquivos Excel nos formatos `.xlsx` e `.xls`.
- **Busca textual:** pesquisa por palavras-chave em diferentes colunas, permitindo encontrar correspondências parciais.
- **Filtros dinâmicos:** criação automática de filtros por coluna com base nos valores disponíveis na planilha.
- **Filtros combinados:** aplicação simultânea da busca textual e de filtros específicos para refinar os resultados.
- **Visualização tabular:** apresentação dos registros encontrados em uma tabela com cabeçalhos e barras de rolagem.
- **Gerenciamento de filtros:** opção para limpar os filtros selecionados e executar novas consultas.
- **Indicadores de status:** exibição da quantidade de registros carregados, dos filtros disponíveis e dos resultados encontrados.
- **Tratamento de erros:** apresentação de mensagens para situações como falhas na importação ou ausência de resultados.

## 🛠️ Tecnologias utilizadas

- **Python** — linguagem utilizada no desenvolvimento da aplicação.
- **Tkinter** — criação da interface gráfica e dos componentes interativos.
- **Pandas** — leitura, manipulação e filtragem dos dados tabulares.
- **Pillow (PIL)** — carregamento e exibição de imagens na interface.

## ⚙️ Como executar

### 1. Pré-requisitos

Certifique-se de ter o Python instalado em sua máquina.

### 2. Clone o repositório

```bash
git clone https://github.com/LuizFernand018/p-search.git
```

Acesse a pasta do projeto:

```bash
cd .\p-search\
```

### 3. Instale as dependências

```bash
pip install pandas pillow openpyxl xlrd
```

O `openpyxl` é utilizado para leitura de arquivos `.xlsx`, enquanto o `xlrd` atende à leitura de arquivos `.xls`. O Tkinter normalmente acompanha a instalação do Python, embora possa exigir instalação separada em alguns sistemas Linux.

### 4. Execute a aplicação

Considerando que o arquivo principal se chama `p-search.py`, execute:

```bash
python p-search.py
```

## 🖥️ Como utilizar

1. Inicie a aplicação.
2. Clique em **Carregar Planilha** e selecione um arquivo Excel.
3. Utilize o campo de busca para pesquisar palavras ou trechos de texto nos registros.
4. Se necessário, selecione valores nos filtros disponibilizados para cada coluna.
5. Clique em **Executar Busca e Filtros** para visualizar os resultados.
6. Utilize **Limpar Filtros** para remover as seleções e realizar uma nova consulta.

A aplicação combina a pesquisa textual com os filtros selecionados, permitindo restringir os resultados de acordo com diferentes critérios.

## 🎯 Objetivos e conhecimentos aplicados

O desenvolvimento deste projeto proporcionou contato prático com conceitos e ferramentas importantes para a construção de aplicações, incluindo:

- Desenvolvimento de interfaces gráficas desktop.
- Manipulação e análise de dados tabulares com Pandas.
- Leitura de arquivos externos e tratamento de exceções.
- Implementação de mecanismos de busca textual e filtragem de dados.
- Criação dinâmica de componentes de interface com base na estrutura de dados.
- Organização da interação entre interface gráfica, processamento de dados e apresentação dos resultados.

## 📚 Contexto acadêmico

Este projeto foi desenvolvido em colaboração com outros estudantes no contexto de uma atividade acadêmica. O código deste repositório foi aproveitado de um repositório anterior utilizado em grupo e está sendo organizado aqui para fins de portfólio e apresentação de experiência prática com Python, interfaces gráficas e manipulação de dados.

## 👤 Autor

Repositório organizado para fins de portfólio por **Luiz Fernando de Melo**.

