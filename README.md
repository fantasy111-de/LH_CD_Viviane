# Análise de Dados com Jupyter Notebook

Este repositório contém um projeto de análise de dados utilizando Jupyter Notebook.

## Estrutura do Repositório

*   `data/desafio_indicium_imdb.csv` : Dados utilizados na análise
*   `../images`: pasta para onde irão os gráficos gerados durante a análise
*   `models/modelo_imdb`: modelo em formato pickle
*   `notebooks/analise.ipynb`: O Jupyter Notebook principal contendo a análise de dados.
*   `requirements.txt`: Lista de todas as bibliotecas Python e suas versões necessárias para executar o projeto.
*   `README.md`: Este arquivo, explicando a estrutura do projeto e como executá-lo.

## Como Instalar e Executar o Projeto

Siga os passos abaixo para configurar e executar o projeto:

### 1. Clonar o Repositório

Primeiro, clone este repositório para sua máquina local:

```bash
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_REPOSITORIO>
```

### 2. Criar e Ativar o Ambiente Virtual

É altamente recomendável usar um ambiente virtual para gerenciar as dependências do projeto. Isso evita conflitos com outras instalações Python em seu sistema.

```bash
python3.12 -m venv venv
source venv/bin/activate  # No Linux/macOS
# venv\Scripts\activate   # No Windows
```

### 3. Instalar as Dependências

Com o ambiente virtual ativado, instale todas as bibliotecas necessárias listadas no `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 4. Executar o Jupyter Notebook

Após a instalação das dependências, você pode iniciar o Jupyter Notebook e abrir o arquivo `analise.ipynb`:

```bash
jupyter notebook
```

Seu navegador padrão será aberto com a interface do Jupyter. Navegue até o arquivo `analise.ipynb` e clique nele para abri-lo. Você poderá então executar as células do notebook para ver a análise de dados.



