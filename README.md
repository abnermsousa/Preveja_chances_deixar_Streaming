# Preveja os usuários com alta chance de deixar seu Streaming

# Sobre o projeto
Neste desafio proposto pela Escola DNC, foi utilizado um modelo de classificação para mapear qual o perfil de
usuários tem mais chance de deixar sua plataforma de streaming, com uma base de dados em csv contendo dados sobre as contas dos clientes.

# Contexto
Você trabalha em uma plataforma de streaming e a diretoria está preocupada com o
alto índice de usuários cancelando as suas assinaturas. Eles acreditam que é possível
prever se um usuário tem mais chance de deixar a plataforma antes que isso aconteça,
e com base nessa informação tomar ações para reduzir o churn.

Seu objetivo é criar um modelo de classificação capaz de prever se um usuário tem
mais chance de cancelar a sua assinatura na plataforma ou não. Para isso, a empresa
forneceu uma base de dados em csv contendo dados sobre as contas dos clientes.
Sobre os dados

# Sobre os dados

Uma adaptação do problema de ecommerce, disponível no Kaggle:
https://www.notion.so/signed/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F75a740fb-4146-455a-8d13-6a24ba56d2c8%2Fstreaming_data.csv?table=block&id=7f01c93d-8cfd-46fb-9f2a-8f0bbd2fbaae&spaceId=6a055055-52ec-4ebb-a697-63027c951344&userId=c0845f00-59fb-4a0f-bb4a-c1e2314cd202&cache=v2

Os dados fornecidos possuem informações sobre as contas dos clientes na plataforma
de streaming, divididos entre contas Basic, Standard e Premium, onde cada uma
oferece uma gama maior de serviços que a anterior.

Coluna | Descrição | Tipo

client_id | Código de identificação do cliente | Int

age | Idade do cliente | Int

gender | Gênero do cliente | String

region | Região de origem do cliente | String

subscription_days | Dias de assinatura ativa do cliente | Int

subscription_type | Tipo de conta | String

num_contents | Quantidade de conteúdos assistidos | Int

avg_rating | Avaliação média dos conteúdos da plataforma | Int

num_active_profiles | Número de perfis ativos na plataforma | Int

num_streaming_services | Quantidade de serviços de streaming que o
cliente possui | Int

devices_connected | Quantidade de dispositivos conectados à conta | Int
churned | Se o cliente cancelou a conta ou não | Int

# Como começar

Desenvolva um modelo de classificação que seja capaz de prever se o cliente irá
cancelar o serviço ou não, levando em consideração o seu perfil no streaming.

Teste com mais de um tipo de modelo para encontrar o que possuir a melhor
performance em comparação com um baseline. Utilize gráficos e visualizações para
auxiliar e enriquecer a sua análise.

Não se esqueça de documentar cada etapa, justificando as escolhas realizadas. É
essencial informar os insights obtidos e como o serviço de streaming pode se beneficiar
do uso do seu modelo para resolver o problema de negócio. 

### Etapas
Análise exploratória dos dados (Data Understanding)
Tratamento dos Dados (Data Preparation)
Modelagem dos Dados - Regressão Logística
Modelagem dos Dados - Tunning
Modelagem dos Dados - Random Forest

# Autor
Abner Miranda de Sousa

Linkedin:
www.linkedin.com/in/abner-miranda-de-sousa-

E-mail: 
abner.miranda.sousa@gmail.com

Instagram:
https://www.instagram.com/abnermsousa/
