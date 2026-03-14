# Auditoria de Segurança: Ataques de Força Bruta com Medusa

## Objetivo
Este projeto documenta simulações práticas de ataques de força bruta contra serviços vulneráveis, utilizando o Kali Linux e a ferramenta Medusa, com foco na compreensão dos vetores de ataque e na proposição de medidas de mitigação.

## Fase 1: Preparação do Ambiente

Para este laboratório, o ambiente foi virtualizado utilizando o **virt-manager/KVM**, adaptando a proposta inicial.

### Importação do Metasploitable 2
Como o Metasploitable 2 não é distribuído nativamente para o virt-manager, foi necessário converter o disco virtual original para o formato `.qcow2`. 
O processo de conversão foi realizado da seguinte forma:

(Leandro, descreva aqui com suas palavras e insira o comando exato que você usou no terminal, colocando-o entre três crases ``` para formatar como bloco de código).

### Configuração das Placas de Rede
Para garantir que as máquinas se comuniquem apenas entre si, criando um ambiente controlado e seguro para os testes, a rede foi configurada da seguinte maneira:

(Leandro, explique aqui como você configurou a rede virtual no virt-manager para isolar o Kali Linux e o Metasploitable 2).
