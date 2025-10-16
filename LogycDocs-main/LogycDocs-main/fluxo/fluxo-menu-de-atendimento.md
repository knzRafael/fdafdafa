# Menu de Atendimento (Flow Builder)



{% embed url="https://www.youtube.com/watch?index=1&list=PLar7QHKGnmri7TBFFHDBIrUDCTVpyQRQE&v=oCGOC4_92cw" %}

**Introdução**\
\
Esta documentação explica a criação de um fluxo de menu dentro do Flow Builder da Logyca Tecnologia, permitindo estruturar atendimentos automáticos.

### Criando um Fluxo no Flow Builder

* Acesse o Flow Builder na plataforma.
* Clique em **Novo Fluxo** e nomeie (exemplo: Atendimento Inicial).
* Clique duas vezes sobre o fluxo criado para abri-lo.
* O primeiro card é o **Início do Fluxo**.

### Configurando um Menu de Opções

* Clique no **+** dentro do card Início do Fluxo.
* Escolha a opção **Menu**.
* Configure a mensagem de boas-vindas:
*
  * Olá `{{name}}`, seja bem-vindo(a) à Logyca Tecnologia!
  * Escolha uma opção abaixo para iniciar seu atendimento:
  * Protocolo de Atendimento: `{{protocolo}}`
* Defina as opções do menu:
*
  * 1 - Comercial
  * 2 - Financeiro
  * 3 - Suporte

### Configurando o Atendimento para Cada Fila

#### Comercial

* Adicione um card **Adicionar Tag** e nomeie como Prospecção.
* Adicione um card **Transferir para Fila** e selecione Comercial.

#### Financeiro

* Adicione um card **Transferir para Fila** e selecione Financeiro.

#### Suporte

* Adicione um card **Transferir para Fila** e selecione Suporte.

### Salvando e Vinculando o Fluxo a uma Conexão

* Clique em **Salvar Fluxo**.
* Acesse **Integrações** e selecione a conexão desejada.
* Escolha o fluxo criado e clique em **Salvar**.

### Testando o Fluxo

* Acesse o WhatsApp conectado à plataforma.
* Envie uma mensagem de teste.
* Escolha uma opção do menu e veja se o atendimento é direcionado corretamente.

### Gerenciamento de Tickets

* Acesse a aba **Atendimentos** e localize o ticket.
* Espie a conversa antes de aceitá-lo.
* Clique em **Aceitar Ticket** para iniciar o atendimento.

### Criando Campanhas para Clientes Marcados com Tags

* Acesse **Campanhas** e clique em **Nova Campanha**.
* Escolha a tag **Prospecção**.
* Defina a conexão e programe o envio.
* Clique em **Salvar e Ativar**.

### Conclusão

O Flow Builder é uma ferramenta essencial para otimizar o atendimento ao cliente. Caso tenha dúvidas, entre em contato com o suporte da Logyca Tecnologia.

**Equipe Logyca Tecnologia 🚀**
