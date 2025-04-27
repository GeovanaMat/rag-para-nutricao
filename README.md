# RAG de Nutrição: Recomendações Personalizadas para Alimentação e Saúde

## Descrição

Este projeto desenvolve uma RAG (Retrieval-Augmented Generation) focada em fornecer recomendações e sugestões personalizadas para a melhoria da alimentação, considerando condições de saúde específicas como obesidade, diabetes e problemas cardiovasculares. O objetivo é auxiliar os usuários a tomar decisões informadas e adaptar seus hábitos alimentares para promover uma vida mais saudável, com base em evidências científicas e diretrizes nutricionais atualizadas.

### Funcionalidades(MVP):
- **Recomendações alimentares personalizadas**: O modelo oferece sugestões de refeições balanceadas e adaptadas para indivíduos com comorbidades, como obesidade, diabetes e doenças cardiovasculares.
- **Análises baseadas em comorbidades**: O sistema considera fatores de saúde do usuário e sugere alternativas alimentares que podem contribuir para o controle e prevenção dessas condições.
- **Busca de artigos científicos**: O modelo facilita a busca por artigos e estudos científicos relevantes sobre nutrição, saúde e gestão de comorbidades por meio da alimentação.
- **Aconselhamento sobre hábitos saudáveis**: Além das recomendações alimentares, o modelo também sugere ajustes nos hábitos de vida, incluindo prática de atividade física e outras orientações para um estilo de vida saudável.

## Objetivo do Trabalho

Este trabalho foi desenvolvido para explorar a aplicação de RAGs no contexto da nutrição, com o objetivo de fornecer apoio na gestão da alimentação e saúde para pessoas com comorbidades. O modelo foi projetado para sugerir melhorias nutricionais que considerem as condições de saúde individuais, promovendo a prevenção e o controle de doenças como obesidade, diabetes e problemas cardiovasculares.

## Como Usar

1. Clone este repositório para sua máquina local.
2. Instale as dependências necessárias usando `pip install -r requirements.txt`.
3. Execute o script principal para iniciar o modelo e interagir com as funcionalidades de recomendação e análise.

## Requisitos

- Python 3.x
- Bibliotecas: `transformers`, `torch`, `faiss-cpu`, entre outras.

## Estrutura de Diretórios

Abaixo está a descrição do propósito de cada diretório no repositório:

- **`data/`**: Este diretório contém os conjuntos de dados utilizados para treinar e testar o modelo. Inclui dados sobre alimentação, comorbidades, artigos científicos e outros recursos necessários para a análise e recomendações personalizadas.

- **`db/`**: Contém os arquivos de banco de dados usados pelo sistema para armazenar e recuperar informações relevantes, como dados do usuário, artigos científicos e histórico de interações.

- **`rag/`**: Este diretório é responsável pela implementação principal da RAG (Retrieval-Augmented Generation). Aqui terá o código que integra o modelo de linguagem com o sistema de recuperação de informações, utilizando fontes externas para gerar recomendações baseadas nos dados fornecidos.

- **`README.md`**: O arquivo de documentação principal do repositório, que fornece informações sobre o projeto, como instalar, usar e contribuir.

- **`requirements.txt`**: Contém a lista de dependências necessárias para executar o projeto, como bibliotecas e pacotes Python. Para instalar todas as dependências, basta rodar o comando `pip install -r requirements.txt`.

- **`scripts/`**: Contém scripts auxiliares para pré-processamento de dados, treinamento do modelo, execução de análises e outras tarefas relacionadas ao desenvolvimento e manutenção do projeto.


