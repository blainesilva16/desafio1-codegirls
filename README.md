# desafio1-codegirls
Repositório para o desafio 1 do curso Santander Code Girls

## Amazon Web Services (AWS) ☁️

A **Amazon Web Services (AWS)** é a plataforma de **computação em nuvem** mais abrangente e amplamente adotada do mundo. A computação em nuvem, de forma simplificada, permite que empresas e indivíduos acessem serviços de tecnologia, como poder computacional, armazenamento de dados e bancos de dados, sob demanda pela internet, com um modelo de pagamento conforme o uso. Isso elimina a necessidade de comprar, gerenciar e manter centros de dados físicos.

### Fundamentos da Infraestrutura e Conta 🌐

A infraestrutura global da AWS é construída em **Regiões** geográficas (como "Leste dos EUA" ou "São Paulo"). Cada Região é composta por múltiplas **Zonas de Disponibilidade (AZs)** isoladas e fisicamente separadas. As AZs são centros de dados com energia, resfriamento e segurança física independentes, que se interconectam com baixa latência, garantindo alta disponibilidade e tolerância a falhas.

Para começar, você precisa **configurar uma conta AWS**. Este é um processo simples que exige um endereço de e-mail e dados de faturamento. Uma vez criada, é crucial proteger a conta usando serviços como o **AWS Identity and Access Management (IAM)**.

### Gerenciamento de Identidade e Custos 👤

No IAM, você define **tipos de usuário na AWS** e suas permissões. Os principais tipos são:

1.  🔑 **Usuário Root da Conta:** O usuário inicial e mais poderoso. **Deve ser evitado** para tarefas diárias.
2.  👥 **Usuários IAM:** Pessoas ou aplicativos com credenciais e permissões específicas e limitadas, definidas por **políticas**.
3.  🔒 **Funções IAM (Roles):** Destinadas a conceder acesso temporário a serviços ou recursos sem a necessidade de credenciais permanentes.

O **controle de custos** é vital. A AWS opera em um modelo **pay-as-you-go** (pague pelo que usar). Para gerenciar isso, a AWS oferece ferramentas como o **AWS Cost Explorer** e **Orçamentos AWS** que ajudam a monitorar o uso, definir alertas e otimizar gastos, garantindo que você não gaste mais do que o necessário.

### Serviços Computacionais e Armazenamento ⚡💾

Dois dos serviços mais fundamentais são o EC2 e o S3:

#### 1. Amazon EC2 (Elastic Compute Cloud) 🖥️

O **EC2** fornece capacidade computacional segura e redimensionável na nuvem, essencialmente **servidores virtuais**. Os principais conceitos são:

* ⚙️ **Imagens AMI (Amazon Machine Image):** Um modelo de software que contém a configuração necessária (sistema operacional, servidor de aplicativos, etc.) para inicializar a instância EC2.
* 🔒 **Security Groups:** Atuam como **firewalls virtuais** que controlam o tráfego de entrada e saída para uma ou mais instâncias EC2.
* 💾 **EBS (Amazon Elastic Block Store):** Oferece **armazenamento em nível de bloco** (como um disco rígido) que pode ser anexado a instâncias EC2.

#### 2. Amazon S3 (Simple Storage Service) 💿

O **S3** é um serviço de **armazenamento de objetos** altamente durável, escalável e seguro. Ele é ideal para guardar qualquer tipo de dado (documentos, backups, vídeos) em sua forma original. Os dados são armazenados em **buckets** (baldes), que são contêineres lógicos. Ele é frequentemente usado para hospedagem de sites estáticos, armazenamento de *data lakes* e backups.
