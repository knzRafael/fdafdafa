# IA no Fluxo de Atendimento



{% embed url="https://www.youtube.com/watch?index=4&list=PLar7QHKGnmri7TBFFHDBIrUDCTVpyQRQE&v=1crLKZkOzX4" %}

Se ainda não configurou sua IA, consulte [Configurar IA](../inteligencia-artificial/configuracao-da-inteligencia-artificial.md).

#### Introdução

A integração da Inteligência Artificial (IA) no fluxo de atendimento permite otimizar a comunicação com os clientes, automatizar interações e melhorar a eficiência da equipe. Com a IA, é possível criar fluxos inteligentes que compreendem as intenções do usuário e fornecem respostas personalizadas.

Esta documentação orienta sobre como configurar a IA no construtor de fluxo (Flow Builder) e quais as melhores práticas para otimizar seu uso.

***

#### Configurando a Inteligência Artificial no Fluxo

**1. Criando um Fluxo com IA**

1. Acesse Flow Builder na plataforma.
2. Crie um novo fluxo e nomeie-o (exemplo: **"Atendimento Inteligente"**).
3. No primeiro card, selecione a opção **"Menu"** e defina as opções de atendimento, como:
4.
   * 1️⃣ Comercial
   * 2️⃣ Suporte
   * 3️⃣ Financeiro
5. Para integrar a IA, utilize um card de **OpenAI** ao invés de transferir para uma fila de atendimento humano.

***

**2. Configurando o Prompt para a IA**

Após vincular a IA ao fluxo, é necessário definir um prompt para guiar as respostas.

1. Acesse **"Integrações" > "OpenAI"**.
2. Edite o prompt conforme sua necessidade, por exemplo:
3.
   * _"Quando o cliente escolher a opção 1, apresente a plataforma de multiatendimento e suas funcionalidades."_
4. Salve a configuração.

📌 **Dica:** Evite instruções vagas. Quanto mais específico o prompt, melhor será a resposta da IA.

***

**3. Vinculando a IA à Conexão de WhatsApp**

1. Acesse **"Configurações" > "Conexões"**.
2. Selecione a conexão de WhatsApp desejada.
3. Ative a opção **"Iniciar Flow por Palavra-chave"**, se necessário.
4. Escolha o fluxo que contém a IA e clique em **Salvar**.

***

#### Exemplo de Uso

📌 **Cenário:**

* Um cliente entra em contato pelo WhatsApp e recebe um menu de atendimento.
* Se ele escolher **"1 - Comercial"**, a IA assume a conversa, apresentando os planos da plataforma.
* Caso necessário, a IA pode transferir o atendimento para um humano.

✅ **Benefícios:**

* ✔ Atendimento mais rápido e personalizado.
* ✔ Redução da carga de trabalho para a equipe.
* ✔ Possibilidade de campanhas para leads que interagiram com a IA.

***

#### Gerenciando a IA no Atendimento

**1. Ajustando Respostas da IA**

Caso a IA forneça respostas indesejadas ou genéricas, revise o prompt:

1. Acesse **"OpenAI" > "Prompt"** e edite as instruções.
2. Teste novamente e valide as respostas.

📌 Se a IA continuar enviando respostas repetitivas, crie um novo modelo de IA na plataforma e vincule-o ao fluxo.

**2. Criando um Funil de Leads com IA**

1. Adicione uma **tag de identificação** (exemplo: "Interesse Multiatendimento") assim que o cliente interagir com a IA.
2. Utilize essa tag para segmentar leads e criar campanhas de reengajamento.

🔹 **Exemplo:** Enviar uma mensagem automática para clientes que mostraram interesse, mas não concluíram a compra.

***

#### Melhores Práticas para Uso da IA

* ✅ Evite respostas vagas: Use prompts específicos para orientar a IA.
* ✅ Acompanhe as interações: Revise conversas para ajustes.
* ✅ Segmente clientes: Utilize tags para organizar os atendimentos.
* ✅ Teste antes de ativar: Valide a IA antes de disponibilizar para clientes.

***

#### Conclusão

A Inteligência Artificial no fluxo de atendimento permite otimizar a comunicação e melhorar a experiência do cliente. Com as configurações corretas, a IA pode automatizar respostas, captar leads e facilitar o trabalho da equipe.

**Caso tenha dúvidas, entre em contato com o suporte.**

🚀 **Equipe Logyca Tecnologia**
