# Criação de uma Conta de Armazenamento Completa no Azure

Este guia fornece instruções detalhadas sobre como criar uma conta de armazenamento completa no Azure, incluindo blobs, arquivos, filas e tabelas.

## Pré-requisitos

- Uma assinatura do Azure
- Acesso ao portal do Azure

## Passos para Criar uma Conta de Armazenamento

### 1. Acessar o Portal do Azure
- Faça login no portal do Azure com suas credenciais.

### 2. Criar uma Nova Conta de Armazenamento
- No menu esquerdo, selecione **"Contas de Armazenamento"**.
- Clique em **"Adicionar"** para criar uma nova conta de armazenamento.

### 3. Configurar a Conta de Armazenamento

#### Nome da Conta
- **Descrição**: Escolha um nome único para sua conta de armazenamento. O nome deve ter entre 3 e 24 caracteres e pode conter apenas letras minúsculas e números.
- **Dica**: Certifique-se de que o nome seja fácil de lembrar e identificar, pois você o usará para acessar os serviços de armazenamento.

#### Grupo de Recursos
- **Descrição**: Selecione um grupo de recursos existente ou crie um novo. Um grupo de recursos é um contêiner que agrupa os recursos relacionados para uma solução Azure.
- **Dica**: Se você está criando um novo grupo de recursos, escolha um nome que reflita o propósito dos recursos agrupados. Isso facilita a organização e gerenciamento.

#### Localização
- **Descrição**: Escolha a região (datacenter) onde a conta de armazenamento será criada. A localização afeta a latência e a disponibilidade dos dados.
- **Dica**: Selecione uma região mais próxima dos seus usuários finais ou do seu local de operações para melhorar o desempenho.

#### Tipo de Conta
- **Descrição**: Selecione o tipo de conta de armazenamento. As opções incluem:
  - **Uso Geral v1**: Suporta todos os serviços de armazenamento, mas não possui os últimos recursos de armazenamento do Azure.
  - **Uso Geral v2**: Suporta todos os serviços de armazenamento com os recursos mais recentes e preços otimizados.
  - **Blob Storage**: Otimizado para armazenar dados de objetos.
- **Dica**: O tipo de conta Uso Geral v2 é geralmente recomendado, pois oferece os recursos mais recentes e opções de preços flexíveis.

#### Redundância de Dados
- **Descrição**: Escolha a opção de redundância de dados para determinar como os dados serão replicados para garantir durabilidade e alta disponibilidade. As opções incluem:
  - **LRS (Locally Redundant Storage)**: Replica os dados três vezes dentro de um único datacenter.
  - **GRS (Geo-Redundant Storage)**: Replica os dados em um datacenter secundário localizado em uma região geograficamente distante.
  - **RA-GRS (Read-Access Geo-Redundant Storage)**: Oferece replicação GRS e acesso de leitura ao datacenter secundário.
- **Dica**: Escolha LRS para dados não críticos e onde o custo é uma preocupação. Para maior durabilidade e disponibilidade, considere GRS ou RA-GRS.

### 4. Criar a Conta
- Clique em **"Revisar + Criar"** para revisar as configurações.
- Clique em **"Criar"** para criar a conta de armazenamento.

### 5. Configurar o Armazenamento
- Após a criação da conta, você pode configurar contêineres de blobs, compartilhamentos de arquivos, filas e tabelas conforme necessário.

## Recursos Adicionais

- [Documentação Oficial do Azure sobre Contas de Armazenamento](https://learn.microsoft.com/pt-br/azure/storage/common/storage-account-create)
- [Tutorial em Vídeo sobre Criar uma Conta de Armazenamento no Azure](https://www.youtube.com/watch?v=-3Wnz_WwrR4)

## Contribuições

Este guia é um projeto colaborativo. Se você tiver sugestões ou melhorias, sinta-se à vontade para contribuir enviando um pull request.

---


