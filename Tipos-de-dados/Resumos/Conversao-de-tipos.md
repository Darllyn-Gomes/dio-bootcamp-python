
# 🔄 Conversão de Tipos em Python

Em Python, a conversão de tipos — também chamada de **type casting** — é essencial quando precisamos **transformar dados de um tipo para outro**, especialmente para realizar operações específicas.

---

## 🎯 Por que converter?

Muitas vezes, você recebe ou armazena valores como `str` (texto), mesmo que o conteúdo represente um número. Para realizar cálculos, é necessário convertê-lo para um tipo numérico.

---

## 📌 Exemplo prático

```python
idade = "25"  # tipo string
print(int(idade) + 5)  # saída: 30
```

> Aqui, convertimos a string `"25"` para o número inteiro `25`.

---

## 🔧 Funções de conversão comuns

| Função      | Descrição                                 | Exemplo               |
|-------------|--------------------------------------------|-----------------------|
| `int()`     | Converte para número inteiro               | `int("10") → 10`      |
| `float()`   | Converte para número decimal               | `float("3.14") → 3.14`|
| `str()`     | Converte para texto                        | `str(20) → "20"`      |
| `bool()`    | Converte para valor booleano (`True/False`) | `bool("") → False`    |

---

## ⚠️ Atenção

Nem todo valor pode ser convertido de forma direta. Por exemplo:

```python
int("texto")  # ❌ gera erro porque "texto" não é um número
```

É importante garantir que o conteúdo seja compatível com o tipo desejado antes de converter.

---

