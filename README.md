# desafiopython3
Terceiro desafio de Python, melhorando o sistema bancário anterior e implementando Programação Orientada a Objetos (POO).
Os principais conceitos aplicados e implementados, foram:

Classe e Objeto: A POO utiliza o conceito de classes para definir a estrutura dos objetos. No código fornecido, temos várias classes, como Cliente, PessoaFisica, Conta, ContaCorrente, Historico, Transacao, entre outras. Os objetos são instâncias dessas classes, criados com o uso do construtor __init__.

Herança: A herança permite que uma classe herde atributos e métodos de outra classe. No código fornecido, a classe PessoaFisica herda da classe Cliente, e a classe ContaCorrente herda da classe Conta. A palavra-chave super() é usada para acessar os atributos e métodos da classe pai na classe filha.

Encapsulamento: O encapsulamento é um princípio que visa esconder a implementação interna de um objeto e fornecer interfaces para interagir com ele. No código fornecido, vários atributos são definidos como privados, usando o prefixo _, como _saldo, _numero, _agencia, _cliente, _historico. Os métodos getter, definidos como propriedades usando o decorador @property, fornecem acesso controlado a esses atributos.

Polimorfismo: O polimorfismo permite que objetos de diferentes classes sejam tratados de maneira uniforme. No código fornecido, a classe Transacao é uma classe abstrata que define os métodos valor e registrar. As classes Saque e Deposito são subclasses de Transacao e implementam esses métodos de forma polimórfica. Isso permite que as transações sejam registradas em uma conta de forma genérica, independentemente do tipo específico da transação.

Abstração: A abstração permite que você modele objetos com base em suas características essenciais. No código fornecido, as classes são projetadas para representar entidades do mundo real, como clientes, contas e transações. A abstração é alcançada por meio da definição de atributos e métodos relevantes para cada classe e omitindo detalhes irrelevantes.
