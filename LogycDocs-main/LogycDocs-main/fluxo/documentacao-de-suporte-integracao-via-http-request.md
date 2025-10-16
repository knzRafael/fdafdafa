# Integração HTTP Request



{% embed url="https://www.youtube.com/watch?index=5&list=PLar7QHKGnmri7TBFFHDBIrUDCTVpyQRQE&v=-Mrnc_Xg84M" %}

#### Introdução

A funcionalidade HTTP Request permite realizar integrações externas com outras plataformas, como CRMs, sistemas de pagamento, ferramentas de automação e muito mais.

Essa funcionalidade é ideal para automatizar processos, capturar informações de clientes e enviar mensagens automáticas com base em eventos específicos.

***

#### Exemplo de Uso

Nesta documentação, demonstraremos como utilizar o HTTP Request para notificar um gestor sobre um cliente que finalizou o funil de atendimento.
Esse mesmo processo pode ser aplicado em funcionalidades como [Notificações de Fatura](../comercial/documentacao-de-suporte-envio-automatico-de-notificacoes-de-fatura-via-whatsapp.md).

***

#### Como Criar um Fluxo com HTTP Request

**1. Criando o Fluxo HTTP Request**

1. Acesse Flow Builder e clique em **Criar Novo Fluxo**.
2. Nomeie o fluxo como **HTTP Request** e clique em **Adicionar**.
3. Clique duas vezes sobre o fluxo e importe um modelo existente ou inicie do zero.

**2. Criando a Lógica do Fluxo**

Dentro do fluxo, serão incluídas as seguintes etapas:

* Iniciar o fluxo e adicionar a tag **"Iniciou Funil"**.
* Enviar mensagem de boas-vindas.
* Enviar imagem ou vídeo explicativo.
* Enviar áudio com informações sobre os planos.
* Capturar variáveis como nome e CPF.
* Exibir um menu para confirmação das informações.
* Se o cliente confirmar, remover a tag **"Iniciou Funil"** e adicionar **"Completou Funil"**.
* Enviar uma notificação via WhatsApp para o gestor.
* Transferir o atendimento para a fila comercial.

***

#### Como Configurar o HTTP Request

1. Acesse o Flow Builder e adicione um bloco **HTTP Request** dentro do fluxo.
2. Configurar os parâmetros HTTP:
3.
   * **Método:** POST
   * **URL:** Utilize o endpoint da API da plataforma
   * **Headers:**
   * ```
     {
       "Authorization": "Bearer SEU_TOKEN",
       "Content-Type": "application/json"
     }
             
     ```
   * **Body (JSON):**
   * ```
     {
       "number": "5511999999999",
       "message": "Lead finalizou o funil."
     }
             
     ```
4. Salvar as Configurações e conectar o bloco HTTP Request no fluxo.

***

#### Integrando a Mensagem de Notificação

* No momento em que o cliente finaliza o funil, o fluxo enviará uma mensagem automática para o WhatsApp do gestor informado.
* O gestor receberá algo como:
* > "Lead finalizou o funil."

***

#### Benefícios do HTTP Request

* ✅ Automatiza integrações sem necessidade de intervenção manual.
* ✅ Notifica gestores em tempo real.
* ✅ Possibilita integração com diversos sistemas externos.
* ✅ Permite captura de informações do cliente e armazenamento em CRMs.

***

#### Considerações Importantes

* ⚠ Essa funcionalidade é recomendada para usuários com conhecimento técnico ou com suporte de um desenvolvedor.
* ⚠ A Logyca Tecnologia não presta suporte para configuração de integrações externas, apenas disponibiliza a funcionalidade.
* ⚠ Caso precise de ajuda, é possível contratar o time de desenvolvimento da Logyca para criar integrações personalizadas.

***

#### Conclusão

O HTTP Request é uma ferramenta poderosa para integração e automação de processos. Ao configurar corretamente essa funcionalidade, você poderá aumentar a eficiência do atendimento e melhorar a gestão de leads e clientes.

**Caso tenha dúvidas, entre em contato com o suporte da Logyca Tecnologia 🚀**
