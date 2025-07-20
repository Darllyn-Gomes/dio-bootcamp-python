
# 💡 Variáveis vs. Constantes em Python

## 🔄 Variáveis

São **identificadores que armazenam valores mutáveis**. Ou seja, podem mudar ao longo da execução do programa.

### 📌 Características
- **Não precisam ter tipo definido previamente** – o Python é uma linguagem de tipagem dinâmica.
- **Precisam receber um valor na criação**.
- Podem ser **reatribuídas** com novos valores facilmente.

```python
nome = "Darllyn"
nome = "Copilot"
```

---

## 🔒 Constantes

Assim como variáveis, armazenam valores, mas a **diferença está na imutabilidade**: uma constante **não deve ser alterada**.

### ⚠️ Observação importante
Python **não possui palavra reservada** para declarar constantes (como `const` ou `final` em outras linguagens).

### 💡 Convenção para constantes
- Nome todo em **maiúsculo**.
- Estilo de escrita **snake_case**.
- Nomes **claros e sugestivos**.

```python
PI = 3.14159
MAX_CONEXOES = 10
```

---

## 🧠 Resumo Visual

| Conceito   | Pode alterar? | Palavra-chave? | Convenção no Python          |
|------------|---------------|----------------|------------------------------|
| Variável   | ✅ Sim         | ❌ Não          | nome_simples                 |
| Constante  | 🚫 Não (por convenção) | ❌ Não          | NOME_EM_MAIUSCULO            |

---


