# Calculadora-de-Paralelogramo

# 📌 List Comprehension - Números Pares Divisíveis por 4  

Este projeto utiliza **List Comprehension** para gerar uma lista contendo apenas números pares que também são divisíveis por 4, dentro do intervalo de 1 a 100.  

## 🔹 Código:
```python
numeros = list(range(1, 101))

# Usando List Comprehension para filtrar os números pares divisíveis por 4
pares_div4 = [numero for numero in numeros if numero % 2 == 0 and numero % 4 == 0]

print(pares_div4)
```

## 🎯 O que o código faz?
1. Cria uma lista de números de **1 a 100**.  
2. Filtra apenas os números que são **pares** e **divisíveis por 4**.  
3. Exibe o resultado final.  

---

Sinta-se à vontade para modificar e testar com outros intervalos! 🚀 
