# trabpoo3bim
Primeiramente iria criar as classes necessárias que vamos usar para o sistema.

Classe Despesa: Representa uma despesa e atributos como descrição, valor, data de vencimento, categoria.
Classe Pagamento: Representa um pagamento e possui atributos como data e valor do pagamento.
Classe DespesaCategoria: Classe abstrata que serve como base para as diferentes categorias de despesas (por exemplo, Alimentação, Transporte, ou seja todas as contas que você paga mensalmente). Essas categorias serão implementadas como subclasses de DespesaCategoria, herdam seus atributos e podendo ser adicionadas mais coisas.
Classe DespesaAlimentacao, DespesaTransporte: Subclasses de DespesaCategoria que implementam comportamentos próprios.
Classe Usuario: Representa um usuário do sistema e contém atributos como login, senha (criptografada) e métodos para cadastrar, editar e listar usuários.



Criando o Menu Principal:

Menu com opções numeradas para cada funcionalidade do sistema (Inserir Despesa,  Pagamento, Listar Despesas, Gerenciar Tipos de Despesa, Gerenciar Usuários e Sair).
Exemplo:
" Digite a funcionalidade que deseja do sistema"
1 - InserirDespesa
2 - Pagamento
3 - ListarDespesas
4 - GerenciarDepesas
5 - Usuários
6 - Sair

Utilizar um switch-case (assim ele teria a opção de sair quando quisesse) para executar a funcionalidade escolhida pelo usuário.
Implementar a funcionalidade de "Inserir Despesa":

Solicitar ao usuário os detalhes da despesa, como descrição, valor, data de vencimento e categoria(gastos mensais).


Criar um objeto da classe Despesa com as informações fornecidas pelo usuário.
Adicionar a despesa a uma lista de despesas armazenada em um arquivo de texto separado.
Implementar a funcionalidade de " Pagamento":

Solicitar ao usuário o número da despesa para a qual deseja  o pagamento.
Criar um objeto da classe Pagamento com a data e valor fornecidos pelo usuário.
Associar o pagamento à despesa correspondente na lista de despesas.
Implementar a funcionalidade de "Listas Despesas":

Utilize um ArrayList para armazenar todas as despesas inseridas pelo usuário.

Solicitar ao usuário o status das despesas que deseja listar (pagas, pendentes) ou a categoria.
Filtrar a lista de despesas de acordo com as preferências do usuário.
Apresentar as despesas em uma  lista.
Apresentar um submenu com opções de "Editar Despesa", "Excluir Despesa" e "Voltar ao Menu Principal".
Implementar a funcionalidade de "Gerenciar Despesa":

Criar um arquivo de texto separado para armazenar os tipos de despesa.
Implementar métodos para criar, editar, listar e excluir tipos de despesa.
Utilizar a classe Scanner para permitir o usuário a atualizar o arquivo de texto.
Implementar a funcionalidade de "Gerenciar Usuários":

Criar um arquivo de texto separado para armazenar os usuários.
Implementar métodos para cadastrar, editar e listar usuários, incluindo a criptografia da senha.
Utilizar a classe Scanner para permitir o usuário a atualizar o arquivo de texto.
Implementar o uso de banco de dados em arquivos de texto:


Implementar o uso de herança, interfaces e polimorfismo:

Criar uma classe abstrata DespesaCategoria que entrará na  categorias de despesas.
Criar subclasses de DespesaCategoria para representar categorias específicas de despesas (por exemplo, Alimentação, Transporte).
Definir interfaces para definir contratos comuns entre as classes (por exemplo, Pagos).

Implementar o uso de métodos e atributos estáticos:

Utilize métodos e atributos estáticos para manter uma contagem global de despesas.
Por exemplo, criar um atributo estático na classe Despesa que é para uma contagem geral


Use a sobrescrita de método para personalizar o comportamento em subclasses. Por exemplo, sobrescreva o método pagar() na classe DespesaTransporte para calcular o desconto no valor da despesa.
