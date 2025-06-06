# 💼 API do Sistema de Transferências Bancárias para Pessoas Físicas

## 🧭 Visão Geral

Este produto tem como objetivo oferecer uma solução moderna, segura e escalável para transferências bancárias entre contas de pessoas físicas. Ele permite que usuários criem contas, realizem transferências e consultem extratos, garantindo rastreabilidade e controle de suas movimentações financeiras.

---

## 🎯 Objetivos do Produto

- Permitir a criação de contas bancárias de forma simples e segura.
- Facilitar transferências entre contas do sistema com as devidas validações.
- Proporcionar acesso fácil ao histórico de movimentações.
- Manter registros claros e confiáveis de todas as operações realizadas.

---

## 🧩 Funcionalidades

### 1. Cadastro de Conta

Permite que uma pessoa física crie uma conta bancária informando:
- CPF (com validação)
- Nome do titular
- Saldo inicial (igual ou superior a zero)

### 2. Transferência entre Contas

Permite a transferência de valores entre contas de pessoas físicas cadastradas no sistema. Regras:
- O valor é debitado da conta de origem e creditado na conta de destino.
- A conta de origem não pode ficar com saldo negativo.
- Transferências acima de R$5.000 exigem uma aprovação adicional.

### 3. Consulta de Extrato

Permite à pessoa física visualizar todas as movimentações financeiras realizadas em um período de tempo, com detalhes de entradas e saídas.

### 4. Registro de Atividades

Todas as operações importantes no sistema devem ser registradas para garantir rastreabilidade e auditoria.

---

## 📐 Regras de Negócio

- Contas devem ser criadas com saldo igual ou superior a zero.
- Nenhuma conta pode ficar com saldo negativo após uma transferência.
- Transferências acima de R$5.000 exigem uma aprovação extra antes de serem concluídas.
- O CPF informado deve ser válido, conforme as regras brasileiras.
- Todas as ações no sistema devem ser registradas para fins de rastreamento e transparência.

---

## ✅ Critérios de Sucesso

- O usuário consegue criar uma conta facilmente, com dados válidos.
- As transferências ocorrem com segurança, respeitando as regras definidas.
- O extrato é claro e acessível, mesmo com alto volume de movimentações.
- As operações são confiáveis, rastreáveis e protegidas contra inconsistências.
