# Guia Passo a Passo: Criando Máquinas Virtuais na Azure

Este repositório contém um guia detalhado para criar máquinas virtuais (VMs) na plataforma Microsoft Azure.

## Índice

- Introdução
- Pré-requisitos
- Passo a Passo
  - 1. Criar uma Conta Azure
  - 2. Acessar o Portal do Azure
  - 3. Criar uma Máquina Virtual
  - 4. Configurar o Firewall
  - 5. Conectar-se à Máquina Virtual
  - 6. Gerenciar a Máquina Virtual
- Recursos Adicionais
- Contribuições
- Licença

## Introdução

Este guia tem como objetivo ajudar você a criar e gerenciar máquinas virtuais na Azure, uma das principais plataformas de computação em nuvem. As VMs são essenciais para hospedar aplicativos, executar cargas de trabalho e muito mais.

## Pré-requisitos

Antes de começar, você precisará:

- Uma conta Microsoft Azure. Se você não tiver uma, pode criar uma aqui.
- Acesso ao portal do Azure.
- Conhecimentos básicos de computação em nuvem.

## Passo a Passo

### 1. Criar uma Conta Azure

Se você ainda não tem uma conta Azure, siga os passos abaixo para criar uma:

1. Acesse o site da Azure.
2. Clique em "Iniciar gratuitamente".
3. Siga as instruções para criar sua conta e obter créditos gratuitos.

### 2. Acessar o Portal do Azure

1. Vá para o portal do Azure.
2. Faça login com sua conta Microsoft.

### 3. Criar uma Máquina Virtual

1. No portal do Azure, pesquise por "Máquinas Virtuais" na barra de pesquisa.
2. Clique em "Criar" e selecione "Máquina Virtual".
3. Preencha os detalhes necessários:
   - **Nome da VM**: Escolha um nome único.
   - **Região**: Selecione a região onde a VM será hospedada.
   - **Imagem**: Escolha o sistema operacional (por exemplo, Windows Server 2022).
   - **Tamanho da VM**: Selecione o tamanho da VM com base nas suas necessidades.
   - **Nome de usuário e senha**: Crie credenciais para acessar a VM.
4. Configure as regras de porta de entrada, permitindo RDP (3389) e HTTP (80).
5. Clique em "Revisar + criar" e depois em "Criar".

### 4. Configurar o Firewall

1. Após a criação da VM, configure as regras de firewall para permitir o acesso.
2. Vá para a página da VM e selecione "Configurações de firewall".
3. Adicione o endereço IP do seu computador ou da rede que precisará acessar a VM.

### 5. Conectar-se à Máquina Virtual

1. Após a implantação, vá para a página da VM.
2. Clique em "Conectar" e selecione "RDP".
3. Baixe o arquivo RDP e abra-o.
4. Insira o nome de usuário e a senha que você criou.
5. Conecte-se à VM.

### 6. Gerenciar a Máquina Virtual

1. No portal do Azure, vá para "Máquinas Virtuais".
2. Selecione a VM que deseja gerenciar.
3. Utilize as opções disponíveis para iniciar, parar, reiniciar ou excluir a VM.
4. Para monitorar o desempenho, acesse a seção "Métricas" e configure alertas conforme necessário.

## Recursos Adicionais

- Documentação Oficial da Azure
- Tutoriais em Vídeo

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.
