## Sistema de Estacionamento - Desafio de Fundamentos

Este projeto foi desenvolvido como parte do curso DIO - Trilha .NET - Fundamentos

O objetivo é aplicar os conhecimentos básicos de C# para criar um sistema de gerenciamento de estacionamento via console.

### Funcionalidades

- Cadastrar Veículo: O usuário insere a placa do veículo para registrá-lo no sistema.
- Remover Veículo: Verifica se o veículo está presente, solicita a quantidade de horas estacionadas e exibe o valor total a ser pago.
- Listar Veículos: Exibe todas as placas dos veículos que estão estacionados no momento.
- Cálculo de Taxas: Realiza o cálculo baseado em um valor inicial e um valor por hora.

### Lógica de Cálculo

O valor total devido pelo cliente é calculado pela seguinte fórmula: $$valorTotal = precoInicial + (precoPorHora \times horas)$$

### Tecnologias Utilizadas

- C#: Linguagem de programação principal.
- .NET: Framework utilizado (Console Application).
- Estruturas de Repetição e Condicionais: Utilizadas para o menu e validações.
- Listas e LINQ: Para armazenamento e busca de dados em memória.
