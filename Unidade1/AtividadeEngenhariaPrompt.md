# Soma dos Números Pares de 1 a 100 em Python

## 📌 Código em Python

```python
# Soma dos números pares de 1 a 100 usando compreensão de lista
soma = sum([numero for numero in range(2, 101) if numero % 2 == 0])
print("A soma dos números pares de 1 a 100 é:", soma)
```

---

## 🧩 Explicação Passo a Passo

1. **Criamos uma sacola chamada `soma`** para guardar o resultado.
2. **Percorremos os números de 2 até 100** com `range(2, 101)`.
3. **Filtramos apenas os pares** usando `if numero % 2 == 0`.
4. **Somamos todos os pares** com a função `sum`.
5. **Mostramos o resultado final** com `print`.

O resultado é **2550**.

---

## 🎒 Analogia para Iniciantes

Imagine que você está andando por uma rua onde cada casa tem um número.  
Você decide visitar **apenas as casas com número par** (2, 4, 6...).  
Em cada casa, o morador te dá uma moeda igual ao número da casa.  
No final do passeio, você conta todas as moedas que juntou — e descobre que tem **2550 moedas**.

---

## 📐 Fórmula Matemática

Os números pares de 1 a 100 formam uma progressão aritmética:

\[
S = \frac{n \cdot (a_1 + a_n)}{2}
\]

- \(n = 50\) (quantidade de números pares)  
- \(a_1 = 2\) (primeiro termo)  
- \(a_n = 100\) (último termo)  

\[
S = \frac{50 \cdot (2 + 100)}{2} = 2550
\]

---

## Referências

- LOPES, Luciano Ramalho. *Python Fluente: Programação Clara, Concisa e Eficaz*. 2. ed. São Paulo: Novatec, 2022.  
  Disponível em: `https://novatec.com.br/livros/python-fluente` [(novatec.com.br in Bing)](https://www.bing.com/search?q="https%3A%2F%2Fnovatec.com.br%2Flivros%2Fpython-fluente")

- SWEIGART, Al. *Automate the Boring Stuff with Python*. 2nd ed. San Francisco: No Starch Press, 2019.  
  Disponível em: [https://automatetheboringstuff.com](https://automatetheboringstuff.com)

- PYTHON SOFTWARE FOUNDATION. *Python Documentation*. 2026.  
  Disponível em: [https://docs.python.org/3/](https://docs.python.org/3/)
```
