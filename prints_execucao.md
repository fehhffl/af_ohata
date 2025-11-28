# Prints de Execução

## Branch Master (Código Original)
![Execução Master](./print_master.png)

### Saída:
```
Resultado = 5
Resultado = 6
Resultado = 15
Resultado = 4
Erro: divisao por zero, operacao irregular
Resultado = 0
Operacao invalida
Resultado = 0
```

## Branch Refatoracao
![Execução Refatoracao](./print_refatoracao.png)

### Saída:
```
5
6
15
4
Divisao por zero nao e permitida
Operador invalido: x
```

## Diferenças Observadas:
- **Master**: Usa `System.out.println("Resultado = " + r)` para cada operação
- **Refatoracao**: Retorna apenas o valor, sem texto adicional
- **Tratamento de erros**: Master usa println, Refatoracao usa exceções