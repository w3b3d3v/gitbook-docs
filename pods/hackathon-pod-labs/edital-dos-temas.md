---
description: Hackathon Pod Labs
---

# Edital dos Temas

## 📣  Anúncios

O Pod Labs está a todo vapor! Estamos anunciando o lançamento dos Temas do Hackathon Pod Labs: Reinventando a Experiência de Aprender.

As premiações são projetadas para ajudá-lo a aprimorar suas habilidades ao mesmo tempo que contribui para soluções inovadoras que podem ajudar a transformar o futuro da educação.

Concluindo as tarefas, você não só estará ganhando conhecimento e experiências valiosas, como também concorre a uma premiação de R$3.000,00 dividida entre 8 categorias (8 grants). E fiquem ligados! Porque mais R$5000 (pós-grant) serão investidos em incubação para os vencedores!



## ⛓️ Solidity

Este tema desafia você a demonstrar o ‘core’ do desenvolvimento e otimização em smart contracts. Imagine um sistema gamificado onde você pode concluir tarefas dentro da comunidade para adquirir: conhecimento, networking, pontos, remunerações e muito mais.&#x20;

Qual seria a pipeline mais adequada para um sistema de Web3 do que o bom e velho Solidity!&#x20;

Desafio: Desenvolver um contrato inteligente em Solidity para administrar o Marketplace de Atividades da Web3Dev.

### O contrato inteligente deve incluir as seguintes especificações:

* Utilizar AccessControl para adicionar membros oficiais e registrados na DAO.
* Permitir que líderes da comunidade criem atividades e membros concluam essas atividades.
* Incluir todos os elementos dentro da estrutura de atividades, marcados como obrigatório no tema de front-end (vide abaixo).
* Liberar remuneração para o endereço que concluiu a atividade quando ambos os líderes aprovarem a conclusão. (on-chain multi-sig).
* Implementar campos de estrutura para comportar atividades, perfis de usuários, tipos de status, incluindo funções de visualização pública para cada variável.
* Implementar uma interface para comunicação com contratos externos.
* Utilizar o padrão ERC721 para mintar NFTs das atividades criadas para o membro.
* Permitir que o usuário dê 'burn' na atividade caso não tenha sido concluída, devolvendo-a para a lista de atividades disponíveis.
* Líderes podem deletar atividades que não foram concluídas caso haja algum erro.
* Emitir eventos para qualquer atividade que altere a blockchain.
* Deve ser de tal maneira que o NFT tenha um token URL próprio na hora do mint, que possa ser alterado pelos líderes e core team.
* Criar um script para fazer upload de metadados no IPFS.

### Critérios de Avaliação:

* Segurança do contrato inteligente: prevenção de ataques conhecidos e uso de práticas recomendadas de segurança.
* Testes robustos: cobertura completa de testes unitários e de integração para todas as funções do contrato, incluindo cenários de sucesso e falha.
* Qualidade do código: organização, modularidade e legibilidade do código Solidity, seguindo as melhores práticas e padrões de codificação.
* Otimização de gás: eficiência no uso de gás para operações do contrato, minimizando custos de transação.
* Interoperabilidade: capacidade do contrato de se comunicar com outros contratos.
* Funcionalidade e lógica do contrato: implementação correta e eficiente dos requisitos e objetivos propostos.
* Governança e controle de acesso: gerenciamento de permissões e autorizações para diferentes funções e participantes no contrato.
* Emissão de eventos: uso adequado de eventos para rastreamento e monitoramento de atividades no contrato.
* Atualização e extensibilidade: facilidade de atualização e modificação do contrato para acomodar novas funcionalidades e mudanças futuras.
* Documentação e comentários: descrição clara e detalhada de como o contrato funciona, incluindo comentários no código e documentação externa.
* Inovação e criatividade: abordagens únicas e soluções inovadoras para os desafios apresentados no projeto.

## 💻 UX/UI Design & Front-end

O objetivo deste tema é desafiar sua criatividade para trazer ideias de componentização e design para um Marketplace. Buscamos o máximo de acréscimos para uma experiência mais amigável, gamificada e ágil do que os modelos atuais apresentam. Concentre-se na reformulação do sistema de atividades remuneradas dos Pods (unidades de trabalho da comunidade), criando a interface de um Marketplace de Atividades inovador e envolvente.

Desafio: Desenvolver o design e/ou o front-end para o Marketplace de Atividades da Web3Dev.

### O Marketplace deve incluir os seguintes elementos:

* Conectar com Metamask.
* Perfil de conta.
* Menu de Pesquisa.
* Atividades devem ser dispostas como NFTs, padrão OpenSea e demais Marketplaces.
* Footer - Informações e redes sociais.

### Cada atividade do Marketplace deve ser vista como um NFT e incluir os seguintes elementos em seus componentes:

* Imagens ou ícones\*
* Título\*.
* Descrição\*.
* Criador da tarefa\*.
* Tags\*.
* Tarefa limitada à\*.
* Progresso ou status da atividade\* (ex: Em andamento, Concluído, Pendente).
* Data limite ou cronograma\*.
* Recompensa em dólar.
* Nível de dificuldade ou classificação (ex: Iniciante, Intermediário, Avançado).
* Comentários e avaliações dos usuários.

\*Obrigatória a presença da informação no layout da atividade, as demais são opcionais.

#### Considere ir além do recomendado e garanta mais pontos proporcionando mais funcionalidades como:

* Filtros de pesquisa avançada para facilitar a descoberta de atividades.
* Sistema de notificações para informar os usuários sobre novas atividades ou atualizações.
* Integração com redes sociais para compartilhar conquistas e promover engajamento.
* Suporte para diferentes idiomas e acessibilidade.
* Estilo e cores da Web3Dev.

### &#x20;Critérios de Avaliação:

* Design responsivo: adaptação a diferentes dispositivos e tamanhos de tela.
* Qualidade do código: organização, modularidade e legibilidade do código.
* Eficiência: Uso eficiente de bibliotecas e frameworks populares, como React ou Vue.
* Performance e otimização: carregamento rápido, uso eficiente de recursos e tempo de resposta.
* Acessibilidade: facilidade de uso para pessoas com deficiências, como contraste de cores, tamanhos de fonte e navegação pelo teclado.
* Navegação e usabilidade: facilidade de uso e intuitividade na interface do usuário.
* Estética e apelo visual: escolha de cores, tipografia, ícones e outros elementos visuais.
* Implementação de animações e interações: efeitos de transição, hover e feedback ao usuário.
* Integração com APIs e contratos inteligentes: conexão bem-sucedida e gerenciamento de dados entre front-end e solidity.
* Documentação e comentários: descrição clara e detalhada de como o projeto funciona e como utilizá-lo.
* Inovação e criatividade: abordagens únicas e soluções fora da caixa para os desafios apresentados.

## 📚 Método de Entrega

1. Cada equipe deve entrar no repositório ‘Hackathon-PodLabs’ dentro do perfil oficial do PodLabs em [https://github.com/devpodlabs/Hackathon-PodLabs](https://github.com/devpodlabs/Hackathon-PodLabs)
2. Dentro do repositório, a equipe deve entrar na branch chamada ‘#1Hackathon’.
3. A equipe deverá criar uma pasta com o nome de sua equipe, contendo o projeto funcional e uma cópia do modelo do arquivo README.md que já está nativamente na branch.
4. A equipe deve commitar seu projeto como um PR (Pull Request) na branch ‘#1Hackathon’.
5. Após feito o PR, se tornará público para toda a comunidade todo o conteúdo postado.
6. O PR deve conter uma descrição clara e concisa do que foi feito, bem como instruções para testar a funcionalidade da tarefa.
7. O PR será revisado pela comissão do Hackathon e por alguns membros do Core Team Web3Dev.
8. O PR deve ser entregue entre o início do evento até o dia especificado no cronograma.
9. Todos os projetos que não infrinjam nenhuma regra do edital ou tenham fuga total do escopo serão tornados públicos.
10. Os vencedores dos grants terão seus projetos em destaque na ‘main’ branch.
11. CUIDADO PARA NÃO COMMITAR CHAVES PRIVADAS!

## 🏆 Premiações: R$3000 🏆

### UX/UI Design (R$700)

1. Melhor layout geral (R$400).
2. Melhores componentes e botões animados (R$180).
3. Melhores ícones, paletas, imagens e tipografia (R$120).

### Front-end (R$1000):

4. Melhor código de front-end do Marketplace de Atividades (R$1000).

### Solidity (js/ts) (R$1300):

5.  Melhor fluxograma do “Marketplace de Atividades” (R$150).

    1. Miro ou outra gratuita.
    2. Deve contar ambos fluxos de solidity e front-end.


6.  Melhor script/interface para fazer upload de metadados no IPFS (R$75).


7.  Melhor script/interface de criação de especificações de metadados (NFTs das atividades) (R$75).

    1. Facilidade para aplicar as descrições nos NFTs usando IPFS.


8. Melhor contrato inteligênte e atendimento às funcionalidades propostas (R$1000):
   1. Funcionalidade e lógica do contrato.
   2. Portabilidade com as propostas de front-end.

### Critérios de desempate:

* Qualidade de código.
* Histórico de commits bem organizados.
* Atendimento às especificações do projeto.
* Segurança do contrato inteligente.
* Testes bem escritos e abrangentes.
* Ideias inovadoras funcionais.
* Otimizações.
* Técnicas padrão de mercado.
* Legibilidade de código e gramática.
* Documentação e referências

### Considerações:

💡 Criatividade e inovação são encorajadas! Pontos extras para recursos adicionais não sugeridos aqui.

🫂 A proposta também incentiva o aprendizado e a troca de ideias dentro da comunidade.

🎁 Pense fora da caixa e explore maneiras inovadoras de melhorar a experiência do usuário na plataforma proposta.

🚀 Com esta proposta, espera-se que os desenvolvedores apresentem soluções criativas e inovadoras para o Marketplace de Atividades, levando em consideração a organização do código, a otimização e a eficiência na utilização de recursos. 🧠&#x20;

## 🚩  Prazos

| Data (2023)    | Agenda                                                   |
| -------------- | -------------------------------------------------------- |
| 10-04          | Início das atividades                                    |
| 24-04 \~ 28-04 | Apresentação dos projetos e última semana de entrega     |
| 03-05          | Divulgação dos resultados e vencedores de cada categoria |

## 📩  Contato

Conheça os canais de atendimento para saber mais sobre o Hackathon Pod Labs: Reinventando a Experiência de Aprender

| Canal de Comunicação     | Função                       | Informação de contato                                                                                        |
| ------------------------ | ---------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Discord (canal Pod Labs) | Suporte                      | [https://discord.com/E66Bs9Ea](https://discord.com/E66Bs9Ea)                                                 |
| E-mail                   | Sugestões, Críticas          | [labs@web3dev.com.br](mailto:labs@web3dev.com.br)                                                            |
| Web3Dev                  | Edital Geral                 | [https://web3dev.com.br/edital](https://docs.web3dev.com.br/pods/hackathon-pod-labs/edital-geral)            |
| Web3Dev                  | Edital dos Temas e Premiação | [https://web3dev.com.br/temas-premios](https://docs.web3dev.com.br/pods/hackathon-pod-labs/edital-dos-temas) |
| Google                   | Formulário de Inscrição      | [https://web3dev.com.br/hacka-form](https://forms.gle/1ashmV7joe7bApzXA)                                     |
