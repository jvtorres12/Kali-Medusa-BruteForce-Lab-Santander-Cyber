# Kali-Medusa-BruteForce-Lab-Santander-Cyber
 Projeto hands-on de Cybersecurity: simulação controlada de ataques de força bruta para fins educacionais. Stack: Kali Linux, Medusa, Metasploitable 2, VirtualBox.  Cenários reais de pentest com documentação completa e medidas de proteção.

# CyberAttack-Lab-Santander



## Descrição do Projeto

Este repositório contém a implementação prática de um laboratório de cybersecurity desenvolvido durante o **Bootcamp Santander Cybersecurity 2025**. O projeto foca em técnicas de **força bruta** utilizando ferramentas profissionais de penetration testing em ambiente controlado.

### O objetivo Principal é demonstrar vulnerabilidades comuns em serviços de rede através de ataques simulados, documentando tanto as técnicas de exploração quanto as medidas de proteção adequadas.

## Tecnologias Utilizadas

- **Kali Linux** - Distribuição especializada em testes de penetração
- **Medusa** - Ferramenta de força bruta multiprotocolo
- **Metasploitable 2** - Máquina virtual intencionalmente vulnerável
- **VirtualBox** - Plataforma de virtualização
- **DVWA** - Damn Vulnerable Web Application

## Cenários de Ataque Implementados

### 1. Ataque FTP (File Transfer Protocol)
- **Alvo:** Serviço FTP do Metasploitable 2
- **Técnica:** Força bruta em credenciais
- **Ferramenta:** Medusa com wordlists customizadas
- **Objetivo:** Explorar credenciais fracas

### 2. Ataque Web (DVWA)
- **Alvo:** Formulários de login da aplicação web
- **Técnica:** Automação de tentativas de login
- **Ferramenta:** Medusa + formulários HTTP
- **Objetivo:** Demonstrar vulnerabilidades em aplicações web

### 3. Ataque SMB (Server Message Block)
- **Alvo:** Compartilhamentos de rede Windows
- **Técnica:** Enumeração e força bruta SMB
- **Ferramenta:** Medusa com protocolo SMB
- **Objetivo:** Explorar compartilhamentos mal configurados


## Medidas de Proteção Identificadas

### Para Serviços FTP:
- Implementar autenticação de dois fatores
- Usar certificados SSL/TLS
- Configurar fail2ban para bloqueio automático
- Política de senhas robustas

### Para Aplicações Web:
- Rate limiting em formulários de login
- CAPTCHA após tentativas falhadas
- Implementar account lockout
- Monitoramento de logs em tempo real

### Para Compartilhamentos SMB:
- Desabilitar SMBv1
- Usar autenticação Kerberos
- Implementar ACLs restritivas
- Network segmentation

## Objetivos de Aprendizagem Alcançados

**Compreender ataques de força bruta** em diferentes serviços (FTP, Web, SMB)  
**Utilizar Kali Linux e Medusa** para auditoria de segurança em ambiente controlado  
**Documentar processos técnicos** de forma clara e estruturada  
**Reconhecer vulnerabilidades comuns** e propor medidas de mitigação  
**Utilizar GitHub** como portfólio técnico para compartilhar documentação e evidências

## Aviso Legal

Este projeto foi desenvolvido **exclusivamente para fins educacionais** dentro do contexto do Bootcamp Santander Cybersecurity. Todos os testes foram realizados em ambiente controlado com máquinas virtuais criadas especificamente para este propósito.

Desenvolvido como parte do **Bootcamp Santander Cybersecurity 2025**

As capturas de tela detalhadas de todos os processos, comandos executados e resultados obtidos estão disponíveis no diretório `/images`.
