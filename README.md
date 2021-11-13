## Projeto de Estacionamento Uniesp

Projeto tem por objetivo fazer um sistema de gestão de estacionamento, onde se pode fazer cadastro de vagas, visualizar vagas e fazer o Check-out.

## Especificações Técnicas

Projeto feito na linguagem java utiliza programação orientada a objetos com ênfase nos conceitos de herança e encapsulamento, além de um pouco de polimorfismo, também é utilizado conceitos de Estrutura de dados para fazer a gestão dos dados inseridos pedidos pelo sistema.

## Para a disciplina de Estrutura de dados

Nome: Lucas dos Santos Alves
Professor: Humberto Barros
Matrícula: 2021111510028

A solução tem roda no terminal utilizando o JDK. Para navegar é necessário colocar a opção desejada, menu inicial: 

![image](https://user-images.githubusercontent.com/79539419/141661307-96501bf4-aee3-4e3d-ba86-ef1de73d1cb7.png)

No menu inicial tem quatro opções, selecionando a opção “1 – Cadastrar vaga” é direcionado para essa tela:

![image](https://user-images.githubusercontent.com/79539419/141661319-42b78529-55d8-4592-8158-268669dad014.png)

Na tela é pedido algumas informações para o cadastro da vaga e no final é gerado um ID para a vaga que pode ser utilizado para localizar a vaga posteriormente, ao final é retornado para o menu novamente, selecionando a opção “2 – Pesquisar vaga” é direcionado para essa tela:

![image](https://user-images.githubusercontent.com/79539419/141661335-bcff3a64-6c58-44bc-b764-35826e222092.png)

Na tela é pedido o ID da vaga que foi gerada no cadastro, após isso é mostrado as informações da vaga e se o usuário deseja liberar ou não, liberando a vaga, uma vaga fica disponível a mais, ao final é retornado ao menu, selecionando a opção “3 – Opções de Administrador” é direcionado para essa tela: 

![image](https://user-images.githubusercontent.com/79539419/141661343-553d0469-837e-4bd7-ab6a-a7e45e4360e5.png)

Como a tela é restrita para administradores é necessário uma palavra para autenticação, quando autenticado é liberado algumas funções, como listar todas as vagas ocupadas, mudar a quantidade de vagas totais e remover uma vaga especifica, ao final é retornado a tela de menu, selecionando a opção “0 – Encerrar” o software encerra.

É utilizado para fazer a gestão de dados do sistema a classe ArrayList, que é criado uma lista de objetos, por ser encadeado não é necessário colocar a quantidade de elementos no momento da instanciação, isso facilita e torna o software mais adaptavel as necessidades de quem utiliza, toda vez que é cadastrado uma vaga é adicionado a lista uma instanciação do objeto com os dados que foram prenchidos pelo usuário, ao final, quando é necessário apagar alguma vaga é localizado utilizando o atributo do objeto "ID" o local onde consta na lista o objeto instanciado e removido utiliando a função "remove" da classe.

## Para a disciplina de Liguagem de Programação II

Alunos: Lucas dos Santos Alves, Lucas Martins Gadelha, Simone Martins de Pontes, Juliana Félix de Souza Gomes, Carlos Henrique dos Santos Carneiro
Professor: Glaucio Bezerra Rocha

Projeto utiliza conceitos de programação orientada a objetos, é utilizado duas classes "Veiculo" e "Usuario", as classes contém conceitos de emcapsulamento, para presevar que seja editado por usuários sem acesso, além de atributos que são objetos, por ser simples as classes generalizam ao maximo os usuários, com o atributo "Função" que é em aberto e pode ser especificado qualquer função (estudante, professor, visitante).
