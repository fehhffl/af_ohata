# Calculadora - Versão Inicial

## Descrição
Este projeto contém a implementação inicial de uma calculadora simples em Java.

## Estrutura
- `src/calculadora/Calculadora.java` - Classe principal com o método calc
- `src/calculadora/TesteCalculadora.java` - Classe de teste

## Compilação e Execução

### Compilar
```bash
javac src/calculadora/*.java
```

### Executar
```bash
java -cp src calculadora.TesteCalculadora
```

## Resultado dos Testes

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

## Observações
- O código utiliza estrutura if-else encadeada para determinar a operação
- A variável de resultado `r` é uma variável de instância pública
- Mensagens de erro são impressas diretamente no console