# Notificações de Fatura



{% embed url="https://www.youtube.com/watch?index=2&list=PLar7QHKGnmrgTZMWNXFb46HcBv0JqlGwP&v=FgwmWY71NXI" %}

#### Introdução

A funcionalidade de automação de envio de notificações de fatura permite que sua empresa envie cobranças automáticas diretamente para o WhatsApp do cliente. Isso melhora a taxa de recebimento e reduz o tempo gasto com cobranças manuais.

A integração suporta diversas plataformas de pagamento, incluindo:

* Asaas
* SGA
* Evo
* Aprove (lançamento em breve)
* Banco Sicoob

***

#### Como Configurar o Envio Automático de Notificações de Fatura

**1. Configuração Inicial**

1. Acesse o menu **"Automações"** dentro da plataforma.
2. Escolha a integração desejada (exemplo: Asaas, SGA, Evo, etc.).
3. Defina a conexão de WhatsApp que será usada para o envio.
4. Escolha o horário de envio (por padrão, é recomendado 9h da manhã).

**2. Inserindo o Token API**

1. Acesse sua conta na plataforma de pagamento (exemplo: Asaas).
2. Vá para a aba **"Integrações"** e clique em **"Gerar nova chave de API"**.
3. Copie o token gerado.
4. Cole o token na plataforma de automação.

**Atenção:** Caso sua empresa já utilize esse token em outra plataforma (como e-commerce ou rastreamento), não gere um novo token sem verificar se a troca afetará suas integrações.

***

#### 3. Configuração das Variáveis

A plataforma permite configurar três regras principais para o envio automático:

**1. Dias antes do vencimento:**

* Defina quantos dias antes do vencimento da fatura a notificação será enviada.
* **Exemplo:** Configurar "5" significa que, todos os dias às 9h, o sistema enviará lembretes para clientes com faturas vencendo em 5 dias.

**2. Intervalo de envio após o vencimento:**

* Selecione a frequência de envio após o vencimento.
* **Exemplo:** Configurar "1" significa que os clientes receberão cobranças diariamente após o vencimento.

**3. Período máximo de inadimplência para envio:**

* Define o prazo máximo para envio de notificação de fatura atrasada.
* **Exemplo:** Configurar "17" significa que apenas clientes com inadimplência de até 17 dias receberão cobranças.
* Caso deseje aumentar esse período, basta ajustar o valor (exemplo: "120" para enviar notificações a clientes inadimplentes há 120 dias).

***

#### Personalização das Mensagens

Todas as mensagens podem ser editadas e personalizadas para melhor se adequarem ao seu atendimento.

* **Mensagem antes do vencimento:**
* ```
  "Olá, sua fatura vencerá em [X] dias. Clique no link para pagamento: [link_do_boleto]"
  ```
* **Mensagem após o vencimento:**
* ```
  "Olá, identificamos que sua fatura está em atraso. Por favor, regularize acessando: [link_do_boleto]"
  ```
* **Mensagem no dia do vencimento:**
* ```
  Envio automático para clientes com vencimento no mesmo dia.
  ```

**Importante:** Utilize as variáveis fornecidas na plataforma para garantir que os dados corretos sejam preenchidos automaticamente.

***

#### Benefícios da Automação de Notificação de Faturas

* ✅ Reduz a necessidade de cobranças manuais.
* ✅ Melhora a taxa de pagamento ao lembrar os clientes.
* ✅ Diminui custos com envios de SMS ou cobranças por e-mail.
* ✅ Aumenta a eficiência do financeiro.
* ✅ Notificações enviadas diretamente no WhatsApp garantem maior taxa de leitura.

***

#### Conclusão

O envio automático de notificação de fatura é uma solução eficaz para garantir que seus clientes recebam e paguem suas faturas em dia.

Ao configurar essa automação, você melhora a gestão financeira da sua empresa e reduz os esforços manuais da equipe.

**Caso tenha dúvidas, entre em contato com o suporte da Logyca Tecnologia. 🚀**
