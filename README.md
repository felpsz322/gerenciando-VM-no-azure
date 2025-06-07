# gerenciando-VM-no-azure

# Gerenciamento de VMs do Azure com System Center Virtual Machine Manager (VMM)

Este documento resume como o **System Center Virtual Machine Manager (VMM)** pode ser utilizado para gerenciar máquinas virtuais (VMs) hospedadas no Microsoft Azure, integrando a administração de ambientes locais com a nuvem.

## Visão Geral

- O VMM é uma ferramenta para gerenciamento centralizado de infraestruturas virtuais, tanto on-premises quanto em nuvem.
- Com o suporte para Azure, o VMM permite a criação, configuração, monitoramento e gerenciamento de VMs diretamente no ambiente Azure.
- Isso facilita a gestão híbrida, unificando operações em ambientes locais e na nuvem.

## Funcionalidades principais

- **Conexão com Azure**: Configuração de credenciais e assinaturas para acessar recursos do Azure.
- **Gerenciamento de VMs Azure**: Permite criar novas VMs, alterar configurações, monitorar status e controlar ciclo de vida das máquinas virtuais.
- **Implantação de Recursos**: Automatiza a implantação de recursos como redes virtuais, discos gerenciados e máquinas virtuais no Azure.
- **Integração com templates**: Uso de templates para padronizar a criação de máquinas virtuais no Azure.
- **Monitoramento**: Permite acompanhar o desempenho e uso das VMs Azure dentro do console do VMM.

## Benefícios

- Gestão híbrida simplificada entre ambiente local e Azure.
- Redução da complexidade operacional ao usar uma única ferramenta.
- Acesso centralizado e controle unificado de VMs e recursos em múltiplos ambientes.

## Requisitos Básicos

- Assinatura Azure ativa.
- Permissões adequadas para criar e gerenciar recursos no Azure.
- Configuração da conexão entre VMM e Azure via certificados ou credenciais.
