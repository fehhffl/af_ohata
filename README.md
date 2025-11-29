# Calculadora - Versão Refatorada

## Descrição
Este projeto contém a implementação refatorada de uma calculadora em Java, aplicando princípios SOLID e boas práticas de programação.

## Estrutura
- `src/calculadora/Calculadora.java` - Classe principal refatorada com métodos separados
- `src/calculadora/TesteCalculadora.java` - Classe de teste com tratamento de exceções
- `docs/` - Documentação JavaDoc do projeto

## Melhorias Aplicadas
- **Separação de responsabilidades**: Cada operação tem seu próprio método
- **Métodos puros**: Sem efeitos colaterais
- **Tratamento de exceções**: Uso de IllegalArgumentException
- **Switch expression**: Substituindo if-else encadeados
- **Documentação JavaDoc**: Documentação completa dos métodos

## Compilação e Execução

### Compilar
```bash
javac src/calculadora/*.java
```

### Executar
```bash
java -cp src calculadora.TesteCalculadora
```

## Gerar JavaDoc
```bash
javadoc -d docs src/calculadora/*.java
```

## Resultado dos Testes Após Refatoração
<img width="638" height="121" alt="Screenshot 2025-11-28 at 23 50 58 2" src="https://github.com/user-attachments/assets/8727d48a-b8a7-42c2-900e-e0b5f3409f3b" />



## Comparação com Versão Inicial
- **Antes**: Código com if-else encadeados e variável de instância pública
- **Depois**: Métodos separados, switch expression, métodos puros sem efeitos colaterais
- **Tratamento de erros**: De println para exceções
- **Documentação**: JavaDoc completo em todos os métodos
