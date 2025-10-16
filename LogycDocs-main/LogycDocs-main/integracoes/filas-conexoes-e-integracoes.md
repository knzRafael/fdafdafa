# Filas e Departamentos

{% embed url="https://www.youtube.com/watch?index=1&list=PLar7QHKGnmrigtP5qvL9U0luGVh7ts3zK&v=0JE9PZyAy-0" %}

#### Introdução

A funcionalidade de Filas, Conexões e Integrações permite conectar a plataforma a serviços externos, como Dialogflow, n8n, Webhooks, Typebot e Smart GPS.

Essas integrações ajudam a automatizar fluxos e direcionar os atendimentos para filas específicas.

***

#### Configuração Inicial

1. **Criar Filas**
   * Acesse **Filas e Departamentos** e crie as filas necessárias (ex.: Comercial, Suporte, Financeiro).
   * Defina uma cor e uma mensagem de saudação para cada fila.
2. **Vincular Usuários**
   * Edite o perfil do atendente em **Usuários**.
   * Selecione as filas que cada usuário pode atender.
   * **Admin:** vê todos os tickets. **User:** visualiza apenas os tickets da fila escolhida.
   * Ative **Ver Tickets em Fila** para permitir que o usuário visualize tickets antes da escolha do cliente.
3. **Conectar o WhatsApp**
   * Vá em **Nova Conexão WhatsApp** e dê um nome à conexão.
   * Integre com [Fluxo de Automação](../fluxo/documentacao-de-suporte-fluxo-de-automacao-de-atendimento.md), IA ou atendimento manual.
   * Defina regras de redirecionamento e mensagens de atendimento.
   * Escaneie o QR Code para conectar o WhatsApp Business.

Após concluir essas etapas, a plataforma estará pronta para o atendimento.

***

#### Configurando Conexões

1. Acesse o menu **"Filas e Conexões"** na plataforma.
2. Escolha a integração desejada:
3.
   * **Dialogflow:** Conexão para criar fluxos de atendimento automatizados.
   * **n8n:** Integração simples para automação de tarefas.
   * **Webhooks:** Permite iniciar uma fila baseada em chamadas de Webhooks externos.
   * **Typebot:** Integração com chatbots configurados no Typebot.
   * **Smart GPS:** Parceria para clientes que utilizam esse serviço.
4. Configurar a Integração:
5.
   * Defina um nome para a integração.
   * Insira os dados necessários (URL do Webhook, código da API, etc.).
   * Clique em **Salvar**.

***

#### Vinculando Integrações a Filas e Departamentos

1. Acesse o menu **"Filas e Departamentos"**.
2. Escolha a fila onde deseja vincular a integração.
3. Selecione a integração criada (exemplo: n8n - Lógica).
4. Salve as configurações.

Agora, quando um cliente entrar em contato e selecionar uma opção no menu, ele será direcionado automaticamente para a integração correspondente.

***

#### Exemplo de Uso

Se você tem um menu com opções como:

* 1 - Comercial
* 2 - Suporte
* 3 - Financeiro

Quando o cliente escolher **1 - Comercial**, ao invés de ser transferido para um atendente humano, a plataforma pode iniciar a integração configurada (exemplo: um fluxo automatizado no n8n).

***

#### Benefícios das Integrações

* ✅ Automatiza atendimentos e otimiza processos.
* ✅ Facilidade na gestão de fluxos de comunicação.
* ✅ Reduz tempo de espera dos clientes.
* ✅ Possibilidade de conexão com diversos serviços externos.

***

#### Conclusão

A funcionalidade de Filas, Conexões e Integrações é essencial para otimizar a operação e automatizar atendimentos.

**Caso tenha dúvidas, entre em contato com o suporte.**

**Equipe Logyca Tecnologia 🚀**
