# Competição DSA de Machine Learning - Edição Junho/2019
# https://www.datascienceacademy.com.br/

Imagine estar com fome em uma parte desconhecida da cidade e receber recomendações de restaurantes, com base em suas preferências pessoais, no momento certo. A recomendação vem com um desconto em anexo da sua operadora de cartão de crédito para um local ao virar a esquina!

Uma Startup pensou nisso e construiu parcerias com comerciantes para oferecer promoções ou descontos aos portadores de cartões de crédito. Mas essas promoções funcionam tanto para o consumidor quanto para o comerciante? Os clientes aproveitam a experiência? Os comerciantes veem resultado? A personalização é fundamental.

Os profissionais da Startup construíram modelos de aprendizado de máquina para entender os aspectos e preferências mais importantes no ciclo de vida de seus clientes, desde alimentos a compras. Mas até agora nenhum deles é especificamente adaptado para um indivíduo ou perfil. É aqui que você entra. Precisando de um modelo preditivo mais robusto, a Startup selecionou você como Cientista de Dados.


## The Goal
 
- Os arquivos dataset_treino.csv e dataset_teste.csv contêm card_ids e informações sobre o próprio cartão - o primeiro mês em que o cartão estava ativo, etc.
- Objetivo é prever um índice de lealdade para cada card_id
- O modelo é avalidado pelo Root-Mean-Squared-Error (RMSE)

## Key features of the model training process in this kernel:
- **Cross Validation:** Using 2-fold cross-validation (para testar mais rapido)
- **Models:** svr, gradient boosting, random forest, xgboost, lightgbm e keras regressors
- **Blending:** Para ter as previsoes finais eu juntei os modelos para obter uma performance melhor
