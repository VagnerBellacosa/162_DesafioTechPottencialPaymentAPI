[**](https://web.dio.me/track/pottencial-net-developer)

##### Desafio Tech Pottencial: Payment API

**

[**](https://web.dio.me/lab/desafio-tech-payment-api/learning/d777f14d-a261-482d-88bd-c1125d54d619)[**](https://web.dio.me/lab/desafio-tech-payment-api/learning/b028e7f2-fe00-4f7b-bbc7-cce096b88908)

<iframe id="ytc20" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" title="Desafio Tech Pottencial Payment API" width="100%" height="100%" src="https://www.youtube.com/embed/hCFRIVHgeKA?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1" sandbox="allow-same-origin allow-scripts allow-forms allow-popups allow-popups-to-escape-sandbox" style="box-sizing: inherit; max-width: none; float: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-size: 14px; vertical-align: baseline;"></iframe>

- CONTEÚDOS
- INFORMAÇÕES

[Desafio Tech Pottencial: Payment API](https://web.dio.me/lab/desafio-tech-payment-api/learning/d777f14d-a261-482d-88bd-c1125d54d619)[Entendendo o desafio](https://web.dio.me/lab/desafio-tech-payment-api/learning/b028e7f2-fe00-4f7b-bbc7-cce096b88908)



- CONTEÚDOS
- INFORMAÇÕES

###### DESCRIÇÃO

No Desafio Tech da Pottencial, você aplicará todos os seus conhecimentos na construção de uma API REST utilizando .Net Core, Java ou NodeJs (com Typescript).

**.NET****C#****Git****GitLab**

------

###### Back-End

###### Avançado

------

###### ESPECIALISTA

![author](https://hermes.digitalinnovation.one/users/author/photos/e58e6c2a-92d3-41c0-abab-784e35e6a442.jpg)

###### Rafael Galvão

Tech Education Analyst, DIO[**](https://www.linkedin.com/in/rafael-galvão-588570145/)



## **INSTRUÇÕES PARA O TESTE TÉCNICO**

- Crie um fork deste projeto (https://gitlab.com/Pottencial/tech-test-payment-api/-/forks/new). É preciso estar logado na sua conta Gitlab;
- Adicione [@Pottencial](https://teams.microsoft.com/Pottencial) (Pottencial Seguradora) como membro do seu fork. Você pode fazer isto em: https://gitlab.com/`your-user`/tech-test-payment-api/settings/members ;
- Quando você começar, faça um commit vazio com a mensagem "Iniciando o teste de tecnologia" e quando terminar, faça o commit com uma mensagem "Finalizado o teste de tecnologia";
- Commit após cada ciclo de refatoração pelo menos;
- Não use branches;
- Você deve prover evidências suficientes de que sua solução está completa indicando, no mínimo, que ela funciona;

## **O TESTE**

- Construir uma API REST utilizando .Net Core, Java ou NodeJs (com Typescript);
- A API deve expor uma rota com documentação swagger (http://.../api-docs).
- A API deve possuir 3 operações:
  1. Registrar venda: Recebe os dados do vendedor + itens vendidos. Registra venda com status "Aguardando pagamento";
  2. Buscar venda: Busca pelo Id da venda;
  3. Atualizar venda: Permite que seja atualizado o status da venda.
     1. OBS.: Possíveis status: 

| `Pagamento aprovado` | `Enviado para transportadora` | `Entregue` | `Cancelada` |
| -------------------- | ----------------------------- | ---------- | ----------- |
|                      |                               |            |             |

- 1. Uma venda contém informação sobre o vendedor que a efetivou, data, identificador do pedido e os itens que foram vendidos;
  2. O vendedor deve possuir id, cpf, nome, e-mail e telefone;
  3. A inclusão de uma venda deve possuir pelo menos 1 item;
  4. A atualização de status deve permitir somente as seguintes transições:
     - **De:** `Aguardando pagamento ` **Para:** `Pagamento Aprovado`
     - **De**: `Aguardando pagamento`  **Para:** `Cancelada`
     - **De:** `Pagamento Aprovado  ` **Para:** `Enviado para Transportadora`
     - **De:** `Pagamento Aprovado  `**Para:** `Cancelada`
     - **De:** `Enviado para Transportador`. **Para:** `Entregue`
  5. A API não precisa ter mecanismos de autenticação/autorização;
  6. A aplicação não precisa implementar os mecanismos de persistência em um banco de dados, eles podem ser persistidos "em memória".

## PONTOS QUE SERÃO AVALIADOS

- Arquitetura da aplicação - embora não existam muitos requisitos de negócio, iremos avaliar como o projeto foi estruturada, bem como camadas e suas responsabilidades;
- Programação orientada a objetos;
- Boas práticas e princípios como SOLID, DDD (opcional), DRY, KISS;
- Testes unitários;
- Uso correto do padrão REST;

**Agora é sua vez de se destacar! Implemente todos os conceitos que aprendemos até aqui para a construção da sua API REST. Seja criativo e aproveite todos os conhecimentos adquiridos até aqui.** 

Bons Estudos! 

