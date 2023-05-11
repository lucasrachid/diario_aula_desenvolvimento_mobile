# diario_aula_desenvolvimento_mobile
Diário de aula

Diario de aula: https://docs.google.com/spreadsheets/d/15S13zfmqAGGMFBtSC4jBQjm9qa6l00PePm_KsR_7hdc/edit?usp=sharing

Atividade 10/02
-> Criar um repositório público para disciplina, onde deverá ser realizado os commits das anotações referentes a aula do dia. Esse repositório irá conter informações a respeito da apresentação da aula, avaliações, plano de ensino, recados, informações de atendimentos entre outras informações.

-> Deverá formar uma equipe até 5 pessoas e buscar livros relacionados a disciplina, fazer o empréstimo e realizar uma apresentação de até 10 minutos a respeito do por que escolheu determinado livro. Deve-se discutir entre a equipe... Apresentação realizada as 21:30. Depois, realizar uma nova pesquisa sobre a profissão, carreiras, vagas no mercado, salário etc sobre Desenvolvimento móbile.
Informações passadas na aula: 
    05/05 - Avaliacao pratica sobre os conceitos abordados.
    Individual e sem consulta.
    Fechamento das entregas do projeto de mobile.

    12/05 - Fechamento diário de aula.
    Retomada de conteúdo.

    19/05 - Recuperação.
    Avaliação dissertativa de todo conteúdo.
    Prova prática e teórica.
    Individual e sem consulta.

Atividade 17/02

Aula a respeito da linguagem a ser estudada em sala, que seria Flutter. Fizemos algumas configurações iniciais na IDE, VS Code para poder rodar o projeto. Foi apresentado algumas informações básicas, mais uma overview do que pode ser feito com o flutter. Ao final da aula teve um desafio para desenvolvermos uma calculadora, algo simples, não precisava conter todas funcionalidades implementadas.

Repositorio: https://github.com/lucasrachid/desenvolvimento-mobile-flutter-2023

Atividade 24/02

-> Aula para ensinar utilizar o terminal configurado do VS Code, utilizando a linguagem dart, para aprender fundamentos sobre funções, com retornos, sem retornos, parâmetros etc. Passou alguns exercícios para praticarmos e enviar no moodle.

Repositorio: https://github.com/lucasrachid/fundamentos_dart

Atividade 03/03
-> Apresentado sobre os tipos de funções e tipos de parâmetros das funções, com parâmetros obrigatórios, parâmetros opcionais, nomeados etc.

Repositorio: https://github.com/lucasrachid/tipos_funcoes_dart

Atividade 10/03
-> Reforçando conteúdo base sobre o DART, com orientação a objetos.
Realizamos a criação de alguns objetos em sala para praticar sintaxe e reforçar o conceito de classes da orientação a objetos

Atividade 16/03
Aula sobre classes
Realizamos exercicios para reforçar o conceito de classes
Repositorio: https://github.com/lucasrachid/classes_dart

Atividade 23/03
Aula sobre widgtes
Realizamos a criação de interfaces gráficas no Flutter, onde explicou como funciona um widget, e no código como deveríamos criar eles.


Atividade 30/03
Aula sobre rotas
Início da aula foi sobre alinhamento de widgets, como funciona o comportamento deles. Quando apresentava algumas propriedades como color, qual teria uma especificade maior. Depois foi apresentado como utilizar o sistema de rotas, sendo que daria para fazer de diversas formas. Também definir qual projeto iria fazer, sendo que deveria conter 10 widgets, deveria ser um projeto reelevante e validado com o professor.
Repositorio: https://github.com/lucasrachid/flutter_rotas 

Repositório do Projeto que foi iniciado: https://github.com/lucasrachid/project_flutter
Embora iniciado o projeto, ainda não tem implementações.

Atividade 13/04<br>
Faltei, porém defini o projeto que gostaria de fazer<br>
Seria um aplicativo para gerenciar automóveis dentro de uma Oficina, contendo as seguintes telas:<br>
1 - Login (Acesso)<br>
2 - Registro (Cadastro ao Aplicativo)<br>
3 - Esqueceu sua Senha (Recuperação de Conta)<br>
4 - Cadastrar veículos <br>
5 - Uma listagem dos veículos cadastrados na Oficina<br>
6 - Informações específicas de um veículo (Após listar, poderia selecionar um veículo, onde iria apresentar os dados do veículo e foto)<br>
7 - Agendamento Serviços (Tela onde poderia agendar o Serviço)<br>
8 - Listar relatório dos serviços prestados (Tela onde iria apresentar uma listagem das ordens de serviços da Oficina)<br>
9 - Cadastro de peças para armazenar na Oficina<br>
10 - Listagem de peças e ferramentas da Oficina<br>
Escolhi esse escopo de projeto, pois não vi ninguém fazendo e penso ter alguma utilidade, não somente acadêmica, mas comercial, visto que<br>
hoje não existe muitos aplicativos que façam isso. Existe sim diversas plataformas online desktop, mas gostaria de estar facilitando ainda<br>
mais a gestão de uma oficina.<br>
Link projeto: https://github.com/lucasrachid/Mech-Manager
Nem todas as telas estão com botão direto na home. Algumas como Informação do carro, é acessado através de outra tela. <br>
Exemplo ao iniciar o app, ir para a home, terá o botão para listagem do carro. Quando você adiciona um veículo a lista <br>
irá incluir o registro na lista, te dando duas ações, 1 de exluir o registro e outra para ir para Info do Veículo, está <br>
segunda opção, irá redirecionar a uma nova rota/widget.

Atividade aula 09/05<br>
1º atividade @@@@ atividade diário de aula<br>
definir 1 campo sobrenome e mostrar o nome e sobrenome no clique<br>
definir 1 campo de sua preferência mostra todos os valores no clique<br>
definir um DTO, inserir os valores dos campos nos atributos e no clique do botão mostrar o DTO<br>
https://docs.flutter.dev/cookbook/forms @@@@ Widgets Quais widgets trabalhamos? R = scaffold, AppBar, Form, Column, TextFormField, Text, ElevatedButtor.<br>
Dentro desses widgets, foi utilizado Key FormState para capturar o formulario, Controller e DTO para trabalhar com o dado.<br>

Repositorio da atividade realizada em aula: https://github.com/lucasrachid/aula_09_maio_desenv_moveis<br>
O que é e para que serve a key de uma widget? Qual a vantegem de ser tipado?<br>
R: O Flutter, é dividido em uma árvore de widgets, sendo necessário uma key para identificar o widget que você deseja capturar.<br>

Definir exemplos práticos e comentários de uso.<br>

Trabalhando com formulários passivos.<br>
Realizar a captura e validação de inputz, dentro de um widget TextField.<br>
restrições (validador, keyboardType, maxLength, inputFormatters, RegExp, outros)<br>
O que é plugin? Para que serve? → o que é? vantagens e desvantagens.<br>
Plugins são implementações prontas que você pode utilizar em seu projeto, que pode acelerar o processo de desenvolvimento, como por exemplo<br>
plugin utilizado em sala, para realizar a máscara de CPF. Pode trazer vantagens, como acelerar o processo de desenvolvimento, ou desvantagens<br>
como por exemplo ficar refém de um plugin de terceiros, uma vez que podem ser vunerávies e não terem mais atualizações.<br>
→ O que é pub.dev? Como funciona? <br>
Pub dev é o site oficial do Flutter, onde a comunidade compartilha plugins, documentações, entre outros.<br>
→ Como escolher um plugin? Justifique. → exemplo de como utilizar/configurar o projeto com explicações passo a passo. componetização → sintaxe → vantagens/desvantagens → POO<br>
A escolha de um plugin vai variar muito de acordo a necessidade de seu projeto. Variando da dificuldade que possa ser realizar uma implementação nativa<br>

Atividade aula 11/05<br>
Repositório: https://github.com/lucasrachid/aula_11_maio<br>
Vantagens Banco Fake<br>
Trabalho em equipe<br>
Isolamento de problemas<br>
Agilizar o desenvolvimento<br>
  
DTO -> Desacoplar a aplicação da necessidade de uma tecnologia específica.<br>
