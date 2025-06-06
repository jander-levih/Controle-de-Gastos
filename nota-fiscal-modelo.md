# Nota Fiscal Simplificada - Modelo

Abaixo está um exemplo de nota fiscal simplificada contendo todos os detalhes que estão disponíveis na planilha financeira do sistema (“Controle de Gastos”). O modelo está estruturado para ser claro e separado por seções, seguindo o que aparece na interface:

---

## Nota Fiscal Simplificada  
**Período:** [Mês/Ano]

---

### 1. Resumo Financeiro

| Descrição            | Valor (R$)           |
|----------------------|----------------------|
| Total de Dívidas     | R$ [Total Dívidas]   |
| Total de Receitas    | R$ [Total Receitas]  |
| Total na Poupança    | R$ [Total Poupança]  |
| **Saldo Final**      | **R$ [Saldo Final]** |

---

### 2. Detalhamento das Movimentações

#### a) Dívidas

| ID  | Mês/Ano | Tipo   | Descrição         | Valor (R$) | Data Pagamento | Pago? |
|-----|---------|--------|-------------------|------------|----------------|-------|
| ... | ...     | Dívida | ...               | ...        | ...            | ...   |

#### b) Receitas

| ID  | Mês/Ano | Tipo    | Descrição         | Valor (R$) | Data Pagamento | Pago? |
|-----|---------|---------|-------------------|------------|----------------|-------|
| ... | ...     | Receita | ...               | ...        | ...            | ...   |

---

### 3. Resumo Mensal

| Mês/Ano | Total Dívidas em Aberto (R$) | Total Receita (R$) |
|---------|------------------------------|--------------------|
| ...     | ...                          | ...                |

---

### 4. Poupança Mensal

| Mês/Ano | Valor Poupança (R$) |
|---------|---------------------|
| ...     | ...                 |

---

### 5. Observações

- Todas as movimentações estão registradas conforme informado na planilha.
- Valores de poupança são informados no campo específico por mês.
- O campo “Pago?” indica se a dívida já foi quitada (“Sim”) ou está em aberto (“Não”).
- Para dívidas parceladas, a descrição apresenta o número da parcela, ex: “Cartão de Crédito (2/3)”.

---

### 6. Geração de PDF

> Caso deseje, utilize o botão “Gerar NF PDF” na planilha para obter uma cópia em PDF desta nota fiscal.

---

**[Seu nome ou responsável]**  
Controle de Gastos

---

> **Observação:**  
> Substitua os campos em colchetes [ ... ] pelos valores reais conforme registrados na aplicação.