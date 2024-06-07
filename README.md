# Preveja_chances_deixar_Streaming(desafio 6)
Utilize um modelo de classificação para mapear qual o perfil de
usuários tem mais chance de deixar sua plataforma de streaming.
Compreender quem é o perfil que está aumentando o churn do seu
negócio é essencial para tomar ações que reduzam essas perdas,
seja alterando critérios na venda ou modificando o produto.

Você trabalha em uma plataforma de streaming e a diretoria está preocupada com o
alto índice de usuários cancelando as suas assinaturas. Eles acreditam que é possível
prever se um usuário tem mais chance de deixar a plataforma antes que isso aconteça,
e com base nessa informação tomar ações para reduzir o churn.

Seu objetivo é criar um modelo de classificação capaz de prever se um usuário tem
mais chance de cancelar a sua assinatura na plataforma ou não. Para isso, a empresa
forneceu uma base de dados em csv contendo dados sobre as contas dos clientes.
Sobre os dados

Uma adaptação do problema de ecommerce, disponível no Kaggle.

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

Desenvolva um modelo de classificação que seja capaz de prever se o cliente irá
cancelar o serviço ou não, levando em consideração o seu perfil no streaming.
