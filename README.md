# DIO - Trilha .NET - Explorando a linguagem C#

## Solução do Desafio DIO

Este projeto é uma solução para o desafio proposto na trilha .NET da [DIO](https://dio.me). O sistema permite cadastrar hóspedes, associá-los a uma suíte e realizar reservas em um hotel, calculando o valor total da estadia conforme o número de dias e aplicando desconto para longas permanências.

## Desafio de projeto

Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de explorando a linguagem C#, da trilha .NET da DIO.

## Contexto

Você foi contratado para construir um sistema de hospedagem, que será usado para realizar uma reserva em um hotel. Você precisará usar a classe Pessoa, que representa o hóspede, a classe Suíte, e a classe Reserva, que fará um relacionamento entre ambos.

O seu programa deverá cálcular corretamente os valores dos métodos da classe Reserva, que precisará trazer a quantidade de hóspedes e o valor da diária, concedendo um desconto de 10% para caso a reserva seja para um período maior que 10 dias.

## Proposta

Confira o diagrama abaixo:
![Diagrama de classe estacionamento](/Images/diagrama_classe_hotel.png)

## Regras e validações

1. Não deve ser possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Se é uma suíte capaz de hospedar 2 pessoas, então ao passar 3 hóspedes deverá retornar uma exception.
2. O método ObterQuantidadeHospedes da classe Reserva deverá retornar a quantidade total de hóspedes, enquanto que o método CalcularValorDiaria deverá retornar o valor da diária (Dias reservados x valor da diária).
3. Caso seja feita uma reserva igual ou maior que 10 dias, deverá ser concedido um desconto de 10% no valor da diária.
