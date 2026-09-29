# Field Ops

## Sobre o projeto

O **Field Ops** é uma plataforma digital para planejamento, execução, acompanhamento e revisão de inspeções técnicas realizadas em campo.

Inspeções de equipamentos e instalações costumam acontecer fora do escritório, em locais com internet instável, e ainda dependem de formulários impressos, planilhas, fotos sem identificação e mensagens informais. Isso causa perda de informações, preenchimento incompleto e pouca rastreabilidade. O Field Ops resolve esse problema com um fluxo digital único, que conecta o trabalho do técnico em campo à gestão administrativa, preservando evidências, histórico e regras de negócio.

## Como a solução funciona

A plataforma completa é formada por quatro componentes:

- **Aplicativo mobile:** usado pelos técnicos para consultar as inspeções atribuídas, identificar equipamentos por QR Code, responder checklists, registrar fotos, observações e não conformidades, inclusive sem conexão com a internet.
- **Interface web administrativa:** usada por administradores e supervisores para cadastrar dados, criar modelos de checklist, agendar inspeções, acompanhar a execução e revisar os resultados.
- **API REST:** centraliza autenticação, regras de negócio, persistência, sincronização e auditoria.
- **Infraestrutura de dados:** banco de dados central, armazenamento local no aplicativo e armazenamento das evidências.

O fluxo principal começa quando o supervisor cria um modelo de inspeção, agenda a atividade e atribui a um técnico. O técnico executa o checklist em campo, os dados são sincronizados e o supervisor revisa o resultado, aprovando ou reprovando a inspeção.

## Protótipo do Painel do Supervisor

Este repositório contém o protótipo web da visão do **supervisor**, o profissional responsável por organizar os cadastros, planejar inspeções, atribuí-las aos técnicos e revisar os resultados enviados após a execução em campo.

O protótipo é responsivo e reúne as seguintes telas:

- Dashboard com indicadores, inspeções recentes e alertas prioritários
- Clientes, locais e equipamentos
- Modelos de checklist
- Planejamento de inspeções
- Acompanhamento das inspeções
- Revisão de uma inspeção concluída

Por ser apenas um protótipo visual, ele usa dados fictícios e não possui backend, banco de dados, API nem login real.

## Tecnologias

HTML5, CSS3, Bootstrap 5 e Bootstrap Icons.

## Integrantes

- Letícia Favero
- Jean Bueno
- Sofia Carolini
- Kathelyn Tourino
