# analise estatistica de diabetes 
Resposta: Os percentuais reforçam os padrões vistos nos gráficos. Alguns exemplos:
- Pressão alta: 75,27% no grupo com diabetes contra 37,42% no grupo sem diabetes.
- Colesterol alto: 67,01% contra 38,13%.
- Problema cardíaco: 22,29% contra 7,27%.
- Dificuldade para andar: 37,12% contra 13,42%.
- Atividade física: 63,05% no grupo com diabetes contra 77,55% no grupo sem diabetes.
- Saúde geral aceitável ou ruim: 40,65% no grupo com diabetes contra 13,42% no grupo sem diabetes.
Esses resultados mostram associações dentro desta amostra. Eles não significam que uma característica, isoladamente, cause diabetes.
Conclusão desta etapa
A análise aponta diferenças consistentes entre os grupos, principalmente em IMC, pressão alta, colesterol alto, problemas físicos, saúde geral e idade. No caso do IMC, a diferença continua estatisticamente significativa mesmo após a retirada dos outliers.
O próximo cuidado é separar significância estatística de importância prática. Como a amostra é grande, valores-p muito pequenos podem aparecer mesmo para diferenças pequenas; por isso, medidas de tamanho de efeito seriam um complemento importante em uma próxima etapa.

## Organização do projeto

```

├── .gitignore         <- Arquivos e diretórios a serem ignorados pelo Git
├── ambiente.yml       <- O arquivo de requisitos para reproduzir o ambiente de análise
├── LICENSE            <- Licença de código aberto (MIT)
├── README.md          <- README principal para desenvolvedores que usam este projeto.
|
├── dados              <- Arquivos de dados para o projeto.
|
|
├── notebooks          <- jupyter notebooks.
│
|   └──src             <- Código-fonte para uso neste projeto.
|      │
|      ├── __init__.py  <- Torna um módulo Python
|      ├── config.py    <- Configurações básicas do projeto
|      └── auxiliares.py  <- funções criadas especificamentes para esse projeto 
|
├── referencias        <- Dicionários de dados, manuais e todos os outros materiais explicativos.
|
├── relatorios         <- Análises geradas em HTML, PDF, LaTeX, etc.
│   └── imagens        <- Gráficos e figuras gerados para serem usados em relatórios
```

## Configuração do ambiente

1. Faça o clone do repositório.

    ```bash
    git clone git@github.com:Trabalhador-pro/Estatistica.git
    ```

2. Crie um ambiente virtual para o seu projeto utilizando o gerenciador de ambientes de sua preferência.

    a. Caso esteja utilizando o `conda`, exporte as dependências do ambiente para o arquivo `ambiente.yml`:

      ```bash
      conda env creat -f > ambiente.yml -- name estatistica 
      ```

## um pouco mais sobre a base

[click aqui](referencias/01_dicionario_de_dados.md). para ver mais sobre os dados

## Resumo dos principais resultados 