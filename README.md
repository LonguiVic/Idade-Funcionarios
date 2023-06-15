# Idade-Funcionarios

Um programa cujo objetivo é calcular a idade dos funcionários de uma empresa utilizando Classes.

Esse código cria uma classe chamada Funcionarios que representa funcionários. Vou explicar cada parte do código:

# Importação do módulo datetime:

from datetime import datetime importa a classe datetime do módulo datetime, que permite trabalhar com datas e horas no Python.


# Definição da classe Funcionarios:

A classe Funcionarios tem um construtor __init__ que recebe três parâmetros: nome, sobrenome e ano_nascimento. Esses parâmetros são usados para inicializar os atributos correspondentes do objeto Funcionarios.


A classe também tem dois métodos:


O método nome_completo concatena o nome e o sobrenome e retorna o nome completo do funcionário.


O método idade_funcionario calcula a idade do funcionário com base no ano de nascimento fornecido no construtor. Ele utiliza a classe datetime para obter o ano atual e subtrai o ano de nascimento do ano atual para calcular a idade.


# Criação de objetos da classe Funcionarios:

Três objetos da classe Funcionarios são criados: usuario1, usuario2 e usuario3. Cada objeto é inicializado com um nome, sobrenome e ano de nascimento diferentes.
Impressão da idade dos funcionários:

O método idade_funcionario é chamado para cada objeto Funcionarios usando a sintaxe Funcionarios.idade_funcionario(objeto).


A idade de cada funcionário é impressa na tela usando a função print.


Portanto, esse código cria uma classe Funcionarios que armazena informações sobre funcionários e fornece métodos para calcular a idade deles. Em seguida, cria objetos dessa classe e imprime a idade dos funcionários.
