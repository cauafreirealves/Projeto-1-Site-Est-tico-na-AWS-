# Projeto-1-Site-Est-tico-na-AWS-
Deploy de um site estatico na nuvem com distribuição global ( S3 e CloudFront)
📌 Descrição

Este projeto consiste em hospedar um site estático utilizando o Amazon S3 e distribuí-lo globalmente através do Amazon CloudFront.
O objetivo é demonstrar conhecimentos em arquitetura de soluções na nuvem e boas práticas de hospedagem de conteúdo estático.

Obs.: O Amazon Route 53 não foi utilizado neste momento, pois ainda não possuo domínio próprio. O acesso é feito pela URL gerada pelo CloudFront.

🛠️ Serviços Utilizados

Amazon S3 – Armazenamento do site estático

Amazon CloudFront – Distribuição de conteúdo com baixa latência e cache global

🚀 Passo a Passo

Criação do Bucket S3

Bucket configurado para hospedagem de site estático

Upload dos arquivos HTML/CSS/JS

Configuração do CloudFront

Criação de uma distribuição apontando para o bucket S3

Testes de acesso pela URL do CloudFront

Validação

Site acessível publicamente pelo endpoint do CloudFront

Exemplo: https://dxxxxx.cloudfront.net

📷 Prints do Projeto

✅ Bucket S3 configurado

✅ Distribuição CloudFront

✅ Site acessível pela URL

(Adicione aqui seus prints)

📚 Aprendizados

Configuração de site estático no S3

Entendimento de CloudFront para distribuição global

Primeira prática de arquitetura serverless e escalável na AWS

🔗 Próximos Passos

Futuramente, integrar com Amazon Route 53 para usar um domínio customizado.
