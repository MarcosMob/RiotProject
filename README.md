# Projeto utilizando a API da Riot Games para conseguir dados e formar um dataset para trabalhar com:
- Extração dos dados :  chamadas à API da Riot, coletando dados de jogadores, partidas e informações sobre as partidas.Depois de extraidos, salvo os dados
em documentos CSV's e carrego para os modelos de Machine Learning trabalharem com eles depois de pré processados.
- EDA : Análise Exploratória dos dados, para descobrir padrões, normalizar e pré processar os dados para os modelos de Machine Learning
- ML : Utilização de modelos para prever vitórias e derrotas dado as partidas de um jogador, no caso utilizei os dados do jogador Arthur Lanches
- Clusterização que relaciona performance e taxa de vitória, dividindo entre partidas de "baixo" e "grande" desempenho, que me confirmou análises feitas na parte exploratória.

## Algumas imagens do projeto
** Dados retirados via API da Riot Games, já salvos em CSV e carregados para um DataFrame **
<div align="center">
  <img width="729" alt="Image" src="https://github.com/user-attachments/assets/417e3eec-6e38-458f-bf81-db6ad1526f6b" /> <br><br>
</div>
** EDA **
<div align="center">
  <img width="729" alt="Image" src="https://github.com/user-attachments/assets/4981ad95-efbd-4308-9b21-8d9094803ae8" /> <br><br>
</div>
<div align="center">
  <img width="729" alt="Image" src="https://github.com/user-attachments/assets/330cb8d5-ea08-4b60-9ebb-ba361cec8221" /> <br><br>
</div>

** Resultados do modelo de classificação **

<div align="center">
  <img width="729" alt="Image" src="https://github.com/user-attachments/assets/68d8afab-7f36-476f-888c-76b5dd54218b" /> <br><br>
</div>

** Kmeans **

<div align="center">
  <img width="729" alt="Image" src="https://github.com/user-attachments/assets/92bac874-04af-4137-92a2-f231295e9fd1" /> <br><br>
</div>
