# Governança

web3dev DAO é de propriedade e governado por detentores de tokens W3D. Nossa política é que as seguintes ações sejam executadas somente após uma proposta e votação bem-sucedidas:

* Alocação de tesouraria (para financiamento, liquidez, investimento)
* Mudanças de provedor de serviço
* Atualizações de tokenomics (incluindo governança, fornecimento, distribuiç

A governança será implementada de forma gradual e em fases. No início, todas as decisões serão tomadas pelos fundadores da web3dev, depois serão tratadas pela comunidade.

<details>

<summary>A governança e votação ocorrerão somente após a venda pública do token W3D.</summary>



</details>

### Ferramentas e Design

<table><thead><tr><th></th><th width="220.33333333333331"></th></tr></thead><tbody><tr><td>Tesouraria</td><td>Seguro para Gnose</td></tr><tr><td>Votação</td><td>Instantâneo da Gnose</td></tr><tr><td>Token de Governança</td><td>W3D</td></tr><tr><td>Proprietário do Cofre da Gnose</td><td>Multi-sinal (2 de 3)</td></tr><tr><td>Proprietário do Gnosis Snapshop</td><td>Multi-sinal (2 de 3)</td></tr><tr><td>Votação Delegada</td><td>Delegar todos</td></tr></tbody></table>

### Propostas

Existem dois tipos de propostas.

#### Proposta de sinal

Uma Proposta de Sinal é algo que qualquer pessoa pode postar na comunidade. Esses votos não são vinculativos, mas se o quórum for alcançado, a proposta será automaticamente atualizada para uma Proposta Principal vinculativa, conforme definido abaixo.

Os membros que consideram enviar propostas devem primeiro detalhar suas ideias nos bate-papos da comunidade para feedbacks, ideias adicionais e para descobrir se há apoio digno para seguir em frente. Supondo que haja um interesse legítimo, um membro pode postar sua proposta.

#### Proposta principal

Uma Proposta Principal é algo que os conselhos do web3dev community apresentam, com opções baseadas em Propostas de Sinais que atingiram o quórum. Esses votos são obrigatórios.

_A ideia de propostas de sinal e núcleo foi inspirada no_ [_AavegotchiDAO_](https://aavegotchi.medium.com/scaling-aavegotchidao-c7e589de0333)_._

### Parâmetros de votação

|                           |                |
| ------------------------- | -------------- |
| Estratégia de instantâneo | 1 W3D = 1 Voto |
| Validação da proposta     | Básico         |
| Limite da proposta        | 1.000 W3D      |
| Duração do voto           | Mínimo 7 dias  |
| Limite de votação         | 1 W3D          |

#### Notas:

* As configurações acima são gerenciadas pelos administradores, que foram indicados pelo web3dev DAO.
* As configurações acima podem ser alteradas pelos membros do web3dev DAO. Pode ser discutido e submetido a votação, após aprovação será alterado pelos administradores.

### Definições

#### Estratégia de instantâneo

Define o peso do voto de cada token.

#### Validação da proposta

A validação da proposta é uma função personalizada para validar se alguém pode postar uma proposta ou não. A validação básica pega o poder de votação e verifica se você passou de um limite definido.

#### Limite da proposta

O Limite da Proposta é normalmente definido como o número de tokens necessários para criar uma proposta.

#### Duração do voto

O período de tempo entre a data de início da votação e a data de término da votação.

#### Limite de votação

O número mínimo de votos necessários para votar em uma proposta.
