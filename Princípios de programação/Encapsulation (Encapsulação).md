#POO
Encapsulamento é um dos pilares da Programação Orientada à Objetos e é utilizado para impedir acessos indevidos  à dados através de **getters** e **setters**, além de agrupar métodos e dados dentro de objetos.

### Getters
Tem como objetivo retornar o valor que é pedido, de um modo que não prejudique a integridade do dado em si.

### Setters
Recebe algum dado como informação para atualizar este mesmo.

No geral, o **Encapsulamento** serve para controlar o acesso aos atributos e métodos de uma classe. É uma forma eficiente de proteger os dados manipulados dentro da classe, além de determinar onde esta classe poderá ser manipulada.

### Exemplo:
```csharp
public class ContaBancaria
{
	public string NumeroCartao {public get; private set;};
	public int Saldo {public get; private set;}; 
	// Estes apenas permitem que só possam ser alterados usando metodos internos, como o AdicionarSaldo()
	
	public void AdicionarSaldo(valor) => Saldo += valor;
}
```