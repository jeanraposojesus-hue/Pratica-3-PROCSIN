# Prática 3: Processamento de Sinais I - Transformada Z

Este repositório contém a resolução da terceira aula prática da disciplina de Processamento de Sinais I. O foco do projeto é a análise de sistemas discretos no tempo, diagramas de polos e zeros, e a implementação de filtros para recuperação de sinais de áudio.

Conteúdo do Repositório

* `Prática3.ipynb`: Notebook Jupyter contendo todo o código Python, derivações matemáticas e visualizações.
* `data_handel.wav`: Arquivo de áudio original utilizado nos experimentos.
* `Aula_Prática_3.pdf`: Roteiro com as 7 questões propostas pelo Prof. Rafael Chaves.

Tecnologias Utilizadas

* **Python 3**
* **Librosa**: Para carregamento e processamento de áudio.
* **Numpy & Scipy**: Cálculos matemáticos e manipulação de sinais.
* **Matplotlib**: Geração de diagramas de polos e zeros e respostas em frequência (Magnitude/Fase).

Principais Análises Realizadas

1.  **Mapeamento no Plano Z**: Identificação de estabilidade através da posição dos polos e zeros.
2.  **Filtragem de Áudio**: Aplicação de sistemas lineares invariantes no tempo (LIT) sobre o sinal `handel.wav`.
3.  **Projeto de Filtros Inversos**: Desenvolvimento de estratégias para mitigar distorções e recuperar o sinal original.
4.  **Análise de Erro (MSE)**: Estudo quantitativo da precisão da recuperação em função da ordem do filtro FIR ($N$).

Conclusões
O trabalho demonstra como a Transformada Z facilita a inversão de sistemas e como a ordem de um filtro FIR impacta diretamente na qualidade da reconstrução de sinais degradados por eco ou interferência.
