# Supermarket

Aplicação Java simples (CLI) que implementa uma lista de compras em memória usando um array fixo.

## Funcionalidades
- Inserir item na lista
- Listar itens (com índice)
- Remover item por índice

## Requisitos
- Java 17
- Maven
- IntelliJ

2.rodar pelo IDE (IntelliJ): execute a classe `main.Main`.

## Uso (exemplo)
- Escolha opção 1 para inserir um item (ex.: `laranja`)
- Escolha opção 2 para listar itens — o formato exibido:
```
############################################
0 - item
1 - item
############################################
```
- Escolha opção 3 e informe o índice para remover um item.

## Estrutura do projeto
- src/main/java/main/Main.java — entrada (CLI)
- src/main/java/implementation/Supermarket.java — interface
- src/main/java/implementation/SupermarketArray.java — implementação com array

## Licença
Projeto para fins educativos — sem licença definida.
