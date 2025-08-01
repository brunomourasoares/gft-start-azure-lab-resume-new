# Conhecimentos em Máquinas Virtuais da Azure

Este documento tem como objetivo orientar e consolidar os principais conceitos e práticas sobre máquinas virtuais (VMs) na Microsoft Azure.

## O que são Máquinas Virtuais na Azure?

Máquinas virtuais são instâncias de computadores virtuais hospedados na nuvem, permitindo executar sistemas operacionais e aplicativos como se fossem servidores físicos.

## Principais Conceitos

- **Tipos de VMs:** Azure oferece diversas séries de VMs (B, D, E, F, etc.), cada uma otimizada para diferentes cargas de trabalho.
- **Imagens:** Escolha entre imagens pré-configuradas (Windows, Linux) ou crie suas próprias imagens customizadas.
- **Tamanhos:** Defina CPU, memória e armazenamento conforme a necessidade do seu projeto.
- **Discos:** Utilize discos gerenciados para armazenamento persistente e backups.
- **Rede:** Configure redes virtuais, IPs públicos/privados e regras de firewall para proteger e conectar suas VMs.

## Principais Tarefas

1. **Criação de VMs**
    - Portal Azure, CLI ou ARM Templates.
2. **Gerenciamento**
    - Iniciar, parar, reiniciar, redimensionar e excluir VMs.
3. **Monitoramento**
    - Utilize Azure Monitor para métricas, logs e alertas.
4. **Segurança**
    - Configure NSG, Azure Bastion, e atualizações automáticas.
5. **Backup e Recuperação**
    - Implemente Azure Backup e snapshots de discos.

## Boas Práticas

- Escolha o tamanho adequado para evitar custos desnecessários.
- Mantenha o sistema operacional e aplicativos atualizados.
- Utilize tags para organização e gerenciamento.
- Automatize tarefas recorrentes com scripts e ferramentas como Azure Automation.

## Recursos para Aprendizado

- [Documentação Oficial Azure VMs](https://docs.microsoft.com/azure/virtual-machines/)
- [Microsoft Learn: Máquinas Virtuais](https://learn.microsoft.com/training/modules/intro-to-azure-virtual-machines/)
- [Exercícios práticos no Portal Azure](https://portal.azure.com/)

## Conclusão

Conhecimentos em máquinas virtuais da Azure é fundamental para administrar ambientes escaláveis, seguros e eficientes na nuvem.
