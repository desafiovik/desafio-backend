# Desafio Backend

## **Sobre a VIK**

Somos um programa de saúde inovador voltado para empresas que veio para transformar o mundo corporativo. Com a utilização de gamificação e estímulos diários, a VIK traz uma abordagem envolvente que faz das atividades físicas uma parte divertida e natural do dia a dia.

https://vik.app

## **Problema:**

Desenvolver uma aplicação ruby on rails para gerenciar convites.

## **Escopo:**

O fluxo do sistema é: ao logar no sistema o administrador pode realizar os seguintes cruds:

- Administradores
    - Adicionar
    - Listar
    - Excluir
    - Editar
- Empresas
    - Adicionar
    - Listar
    - Excluir
    - Editar
- Convites
    - Adicionar
    - Listar
    - Excluir
    - Editar

## **Regras:**

- Fluxo de login, só precisa logar e fazer logout, não há necessidade de recuperar senha.
- Uma empresa pode ter vários convites
- Um usuário pode ser convidado por mais de uma empresa
- Criar um filtro na tela de convites por nome, empresa e/ou intervalo de tempo. Exemplo: Digamos que a empresa A tem 10 convites ativos no mês de Janeiro e em Fevereiro 2 convites foram desativados. Ao realizar o filtro em Janeiro deve aparecer 10 convites e em Fevereiro 8 convites.

## **Expectativas:**

- Faça commits atômicos e progressivos.
- Trabalhe a separação de responsabilidades na aplicação.
- Trabalhe a representação dos conceitos, faça uso de bons nomes em variáveis, métodos, classes, módulos/namespaces.
- Trabalhe requisitos não funcionais como: segurança, performance, disponibilidade, confiabilidade, observabilidade, manutenibilidade.
- O design das telas fica de sua preferencia, não iremos analisar o design das telas;

## **Entrega:**

Crie o projeto suba em um repositório e nos envie o link do repositório para `frankyston.lins@vik.app`

## **Contexto: O que utilizamos / fazemos na VIK.**

1. Ruby 3.1.0 e Rails 7.0, estamos nos preparando para atualizar ambos. Então pedimos que teu teste use dessas versões para cima.
2. Fazemos uso de casos de uso para encapsular as regras negócio. Ou seja, nós não implementamos o código diretamente nos controllers, models, jobs. Todo ponto de entrada delega a operação para um caso de uso (1).
3. Testes: Rspec, factory bot, shoulda matchers.
4. Namespaces: Curtimos muito modularizar o código, ao agrupar classes, módulos, constantes que tenham relação ao conceito / domínio que representam.
5. Bons nomes para métodos, constantes (classes e módulos), namespaces.
6. Garanta que o setup seja fácil e que tanto a aplicação quanto o teste rodem. Pode não parecer, mas recebemos diversos testes que ao fazer o git clone e realizar o setup o projeto não rodava de primeira. Nosso time teve de ajustar N entregas para conseguir avaliar o que foi feito (mas isso não é legal e tira pontos de quem aplicou).
7. Se tiver confortável com Docker, use-a, usamos aqui na VIK também, será mais fácil para testar sua aplicação.

PS: Sinta-se a vontade para apresentar sugestões, práticas na qual você acredita serem melhores. ;)
