

# 🐍 Modo Interativo do Python

O modo interativo é uma funcionalidade poderosa do interpretador Python que permite ao desenvolvedor **executar código e ver os resultados em tempo real**. Ideal para testes rápidos, explorações e estudos.

## 🚀 Como Iniciar o Modo Interativo

Você pode iniciar o modo interativo de duas formas:

- **Executando apenas o interpretador**:
  ```bash
  python
  ```

- **Rodando um script com a flag `-i`**, que mantém o modo interativo após a execução do script:
  ```bash
  python -i app.py
  ```

---

## 🧭 Explorando com `dir()` e `help()`

### 📂 `dir()`
Retorna uma lista de nomes definidos no escopo atual ou os atributos de um objeto especificado.

- **Sem argumentos**:
  ```python
  dir()
  ```
- **Com argumento**:
  ```python
  dir(100)
  ```

### 📚 `help()`
Invoca o sistema de ajuda interativo do Python. Pode ser utilizado para acessar documentação sobre módulos, funções, classes e objetos.

- **Modo interativo**:
  ```python
  help()
  ```
- **Consultando documentação específica**:
  ```python
  help(100)
  ```

---

💡 **Dica**: Essas ferramentas são especialmente úteis para explorar pacotes desconhecidos, verificar os atributos disponíveis em objetos e aprender diretamente na prática.

---


