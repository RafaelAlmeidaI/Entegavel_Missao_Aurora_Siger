Sistema de Monitoramento e Análise de uma Nave
Sobre o projeto

Este projeto foi desenvolvido para uma atividade integradora com o objetivo de simular um sistema de monitoramento de uma nave espacial.
O programa foi desenvolvido em Python e recebe dados de telemetria para verificar as condições da nave antes da decolagem.
São analisados dados como temperatura interna e externa, integridade estrutural, nível de energia, pressão dos tanques e funcionamento dos módulos.
O sistema também realiza uma análise energética, identifica possíveis anomalias e calcula um índice de risco.

Objetivo

O objetivo do projeto é utilizar programação e análise de dados para criar um sistema capaz de verificar as condições da nave e auxiliar na tomada de decisão sobre a decolagem.
Dados analisados
Os dados utilizados pelo programa são:
Temperatura interna;
Temperatura externa;
Integridade estrutural;
Nível de energia;
Pressão dos tanques;
Status dos módulos críticos.
Funcionamento

Primeiramente, o usuário informa os dados da nave.
Depois, o programa verifica cada informação de acordo com os limites definidos.
Caso algum parâmetro esteja fora das condições estabelecidas, a decolagem é abortada.
Caso todos os parâmetros estejam dentro dos limites, o sistema informa:
"PRONTO PARA DECOLAR"
O programa também mostra as possíveis anomalias encontradas, calcula a autonomia energética e apresenta o índice de risco.

Análise energética
Para a simulação foi utilizada uma bateria com capacidade total de 200 kWh.
O programa calcula a energia disponível de acordo com o nível da bateria e considera o consumo e as perdas durante a operação.
A fórmula utilizada é:
Autonomia = Energia disponível - Consumo - Perdas

Índice de risco
O sistema possui um índice de risco que varia de 0 a 100.
A classificação utilizada é:
0 a 20: Baixo
21 a 50: Moderado
51 a 80: Alto
81 a 100: Crítico
Esse índice foi criado apenas para a simulação do projeto e não representa uma probabilidade real de acidente.

Tecnologias utilizadas
Python
Git
GitHub
vs code

Como executar
Para executar o projeto, abra o arquivo sistema_monitoramento.ipynb em um ambiente que suporte Jupyter Notebook, como o Visual Studio Code, Jupyter Notebook ou Google Colab.
Depois, execute as células do notebook e informe os dados solicitados pelo programa.

Prints da execução







Arquivos do projeto
README.md – documentação do projeto.
sistema_monitoramento.ipynb – notebook com o código e as execuções.
sistema_monitoramento.py – código principal do sistema.
Repositório

Link do GitHub:




  
