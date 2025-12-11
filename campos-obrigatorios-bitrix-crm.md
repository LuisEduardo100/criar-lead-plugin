# 📋 Guia de Campos Obrigatórios - Kinbox/Bitrix

Este guia serve para garantir que todos os dados necessários sejam preenchidos antes de enviar o negócio para o CRM, evitando erros na automação.

---

## 1. O "Porteiro" (Obrigatório Sempre)
⚠️ **Atenção:** O sistema verifica este campo primeiro. Se ele estiver vazio, nada acontece.

- [ ] **Tipo de Orçamento**
  *(No sistema: `aled_tipo_de_orcamento`)*

---

## 2. Fluxo VAREJO
**Quando usar:** Se o *Tipo de Orçamento* for selecionado como **"Venda Direta"** ou **"Venda Direta Decorativo"**.

### Campos Obrigatórios:
- [ ] **Origem**
- [ ] **Estado (UF)** *(campo: `[x]_estado`)*

---

## 3. Fluxo PROJETO (Negócio)
**Quando usar:** Para **todos os outros** Tipos de Orçamento (ex: Arquitetura, Construtora, Corporativo, etc).

### Campos Obrigatórios:
**Dados Básicos:**
- [ ] **Origem**
- [ ] **Cidade**
- [ ] **Estado (UF)**
- [ ] **Novo Lead?**

**Dados do Profissional/Obra:**
- [ ] **Status do Profissional**
- [ ] **Segmento de Mercado**
- [ ] **Segmento da Obra**
- [ ] **Tipo de Obra**
- [ ] **Classificação da Obra**

**Dados do Orçamento:**
- [ ] **Perfil do Orçamento Principal**
- [ ] **Precisa de Orçamento Similar?**

---
*Gerado automaticamente pela equipe de Automação.*