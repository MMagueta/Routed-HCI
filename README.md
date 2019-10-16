# Introdução
## Sobre

Este relatório corresponde à implementação de uma pesquisa de usuário para a idealização de um protótipo de alta fidelidade, que condiz a um aplicativo cujo objetivo é facilitar o rastreio e envio dos produtos a serem entregues por transportadoras, assim como as metodologias utilizadas pelo grupo e os resultados obtidos.

A seguir serão discutidos a proposta do aplicativo *Routed*, as metodologias aplicadas pelos integrantes do grupo, sendo estas a realização de um questionário geral para a idealização do consumidor, seguido de entrevistas específicas com foco maior nas concepções do aplicativo e questões de usabilidade. A estratégia de *shadowing* foi utilizada para ter uma base de comportamento dos usuários vendedores e que utilizarão o sistema de entrega para verificar os produtos enviados, observando perfis de rede social em grupos de troca e venda de produtos. Após a reunir informações suficientes sobre os usuários, uma pesquisa sobre outras tecnologias e aplicativos parecidos foi feita, buscando observar os recursos do mercado e tendências, todas essas informações servirão de base para a construção do aplicativo.
## Proposta
O aplicativo de alta fidelidade proposto, *Routed*, possui como ideia central  ser uma plataforma para gerenciamento e atualização de entregas, facilitando a organização e visualização dos produtos enviados ou a serem recebidos pelo usuário. O aplicativo tem ideia do usuário entrar com contas das principais lojas e os pedidos postados e atualizados serem filtrados para um mesmo local de fácil acesso e organização. 
# Metodologias
## Look
### Shadowing

Foram observados processos de vendas informais em grupos de redes sociais. Estas vendas correspondem à grande parte do ideal creditado ao protótipo em questão, portanto entender o processo de interação dos indivíduos em um ciclo de exposição, negociação, venda, monitoração e por fim, validação. Para a análise experimental, dois vendedores foram analisados em um processo de venda, além disso, um comprador em contraponto.

#### Vendedor

O primeiro vendedor observado anunciou um produto às 17:45, pontualmente, da sexta-feira, clamando ser o horário de pico e de maior visualização nos grupos. O produto consistia em "*amiibos*" de certo grau de demanda, porém comuns. O preço estava um pouco abaixo da média em que os outros foram vendidos. Dois minutos depois, outros dois usuários da plataforma de vendas do Facebook comentaram barganhando e indagando o frete para os respectivos endereços. Prontamente por uma tabela, o vendedor consultou a faixa de frete considerando aumentar um pouco o lucro com a entrega. As opções de entrega foram anunciadas, envio via PAC/Sedex ou entrega pessoal. A entrega pessoal foi descartada quase que de imediato na negociação por limitantes de distância. Logo em seguida, dos possíveis compradores, ambos começaram a discutir acerca da venda, sobre quem havia direito de compra sobre o item (único), iniciando um leilão. O vendedor escolheu um usuário que apareceu logo em seguida oferecendo um valor ligeiramente maior. Logo em seguida, a negociação ocorreu por chat. Algo interessante a ser mencionado é que, o comprador em questão não aparentou estar apreensivo na compra informal; o vendedor apenas o enviou um código QR code um aplicativo de pagamentos, que foi pago com prontidão, após isso o endereço foi requisitado, o vendedor informou o frete, levando em outro QR code. Segundo o vendedor, o produto seria postado na manhã da segunda em alguma agência dos Correios, e de fato foi, seguido do envio imediato de uma foto do vendedor com o produto ainda na agência para o cliente, acompanhado do código de rastreio. Na quarta o produto foi recebido e validado pelo cliente, seguido de um comentário no anúncio agradecendo e avaliando o vendedor. É perceptível que existe um grau de confiança entre os vendedores. Em uma entrevista com o vendedor, foi levantado um evento em que o cliente tentou burlar o pagamento alegando que o produto não havia sido entregue, com o objetivo de causar más interpretações ao vendedor, manchando a sua reputação, porém a comunidade de compra e venda levantou apoio ao vendedor, comentando todas as situações de "honestidade" apresentadas até então.

#### Comprador

## Learn
### Competitive Survey - Avaliação Heurística
#### Heurísticas
1. Visibilidade do estado do sistema;
2. Correspondência entre o sistema e o mundo real;
3. Controle e liberdade do usuário;
4. Consistência e padronização;
5. Prevenção de erros;
6. Reconhecimento em vez de memorização;
7. Flexibilidade e eficiência de uso;
8. Projeto estético e minimalista;
9. Auxilia os usuários a reconhecerem, diagnosticarem e se
recuperarem de erros;
10. Ajuda e documentação.

#### Plataforma avaliada: Correios

 - Tempo de carregamento; [1]
 - Dubious permissions; [2]
 - Inconsistent inputs at the “login screen”; [10]
 - Fields with no detailed description (phone field, for instance); [10]
 - No feedback for actions or whatsoever (login example); [9]
 - Call system of token retrieval with non existent number; [9]
 - Home screen empty with just a few options non consistent to the app
   purpose; [8]
 - Lack of consistency with the other apps from the same company, split
   into several independent (and redundant) modules; [4]
 - Options linking other series of apps (Correios Celular, for
   instance); [4]
 - Duplicate options in the same screen; [3]
 - Timeline with inconsistent text (hard to note important features);
   [6]
 - Incorrectly named features and wrong icons (Senhas de atendimento is
   about time spent in the agency); [6,2]
 - Options “broken”, dependant of other options (Senhas de atendimento);
   [7]
 - App stops running when a search of address is made; [9]
 - Useless inputs, such as addressee and mailer (in the address form).
   [2]
#### Severidade

