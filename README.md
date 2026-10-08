# Ecommerce Checkout — Testes Unitários com xUnit

Projeto desenvolvido para praticar testes unitários em C# com .NET 10 e xUnit.

## Funcionalidades

### 1. GerarCodigoRastreio

Recebe uma região e o número do pedido e gera um código de rastreio.

Exemplo: `sudeste, 42` → `SUDESTE-0042`

### 2. CalcularPontosFidelidade

Calcula os pontos de fidelidade com base no valor da compra.

Exemplo: `150` → `30 pontos`

### 3. TemDireitoAFreteGratis

Verifica se o cliente tem direito ao frete grátis quando o valor da compra é de pelo menos 200 ou quando é cliente VIP.

## Testes automatizados

Os testes foram implementados com xUnit e utilizam:

* `Assert.Equal`
* `Assert.True`
* `Assert.False`

## Como executar

Na pasta principal da solução, execute:

```bash
dotnet build
dotnet test
```

## Tecnologias

* C#
* .NET 10
* xUnit
